# End-to-End Schema
![pipeline](https://user-images.githubusercontent.com/98518827/229811525-ec80d440-870e-451e-9ed3-1c985386acf1.jpeg)



## General Installation Guide

====================
- Prerequisite:

    A. Python 3: [Install Here](https://www.python.org/downloads/)
    
    B. Docker and Docker Compose: [Install Here](https://docs.docker.com/engine/install/ubuntu/)
    
    C. Google's Credential Service Account used for GCS and Bigquery access: [Get Here](https://developers.google.com/workspace/guides/create-credentials)
    
    D. Kafka: [Install Here]([https://docs.getdbt.com/docs/get-started/pip-install](https://kafka.apache.org/quickstart))
    
    E. Airflow : [Install Here]([https://docs.docker.com/engine/install/ubuntu/](https://airflow.apache.org/docs/apache-airflow/stable/installation/index.html))
    
    ### Penggunaan
End-to-end data pipeline is the process of collecting data from multiple sources, cleaning, processing, and entering it into a system that can be used for analysis.

Cloud Storage: Initial data will be stored in cloud storage. Here, data can be stored in various formats such as CSV, JSON, or parquet.

Apache Kafka: After the data is stored in cloud storage, Apache Kafka will be used as a third party in the data pipeline process. Kafka is an open source data streaming platform that enables real-time or streaming data delivery. Data can be moved from cloud storage to Kafka using Kafka Connect.

BigQuery: Data that is in Kafka will be entered into BigQuery. BigQuery is a cloud data warehouse that enables large-scale data processing and data analysis across an organization. In BigQuery, data can be managed and stored in structured tables and then used for analysis.

Looker Studio: Once data is entered into BigQuery, Looker Studio will be used as a platform to visualize and analyze data. Looker Studio is a Business Intelligence (BI) platform that enables users to create reports and dashboards, perform data analysis, and share information with teams in real-time.
   
