# Cybersecurity: Suspicious Web Threat Interactions

This project focuses on detecting and analyzing patterns in web interactions to identify suspicious or potentially harmful activities. The analysis is performed using machine learning techniques with Python, SQL, and Excel.

## Project Overview

### Objective

The primary objective is to detect and analyze patterns in web interactions to identify suspicious or potentially harmful activities. [cite: 268, 269]

### Dataset

The dataset contains web traffic records collected through AWS CloudWatch, aimed at detecting suspicious activities and potential attack attempts. [cite: 254] It includes various features extracted from web traffic to a production web server. [cite: 255, 256, 257, 258, 259]

You can download the dataset from the following link:

[Click here to download data set]

### Dataset Description

Each entry in the dataset represents a stream of traffic to a web server, with the following columns: [cite: 259, 260, 261, 262, 263, 264, 265]

* `bytes_in`: Bytes received by the server. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `bytes_out`: Bytes sent from the server. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `creation_time`: Timestamp of when the record was created. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `end_time`: Timestamp of when the connection ended. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `src_ip`: Source IP address. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `src_ip_country_code`: Country code of the source IP. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `protocol`: Protocol used in the connection. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `response.code`: HTTP response code. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `dst_port`: Destination port on the server. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `dst_ip`: Destination IP address. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `rule_names`: Name of the rule that identified the traffic as suspicious. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `observation_name`: Observations associated with the traffic. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `source.meta`: Metadata related to the source. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `source.name`: Name of the traffic source. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `time`: Timestamp of the detected event. [cite: 259, 260, 261, 262, 263, 264, 265]
    
* `detection_types`: Type of detection applied. [cite: 259, 260, 261, 262, 263, 264, 265]

### Potential Uses

This dataset is ideal for: [cite: 265, 266, 267]

* **Anomaly Detection:** Developing models to detect unusual behaviors in web traffic. [cite: 265, 266, 267]
    
* **Classification Models:** Training models to automatically classify traffic as normal or suspicious. [cite: 265, 266, 267]
    
* **Security Analysis:** Conducting security analyses to understand the tactics, techniques, and procedures of attackers. [cite: 265, 266, 267]

## Getting Started

### Prerequisites

* Python 3.x
* Libraries: pandas, matplotlib, seaborn, scikit-learn, tensorflow

### Installation

1.  Clone the repository:

    ```bash
    git clone <repository_url>
    ```
    
2.  Install the required libraries:

    ```bash
    pip install pandas seaborn scikit-learn tensorflow
    ```
    

### Project Structure

The project is organized as follows:
├── data/
│   └── cybersecurity_data.csv  # Dataset
│
├── notebooks/
│   └── <notebook_name>.ipynb  # Jupyter Notebooks
│
├── scripts/
│   └── <script_name>.py       # Python scripts
│
└── README.md

