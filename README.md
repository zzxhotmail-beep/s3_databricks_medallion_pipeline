# 🚀 End-to-End Data Pipeline with S3 & Databricks (Bronze–Silver–Gold Architecture)

## 📌 Project Overview

Designed and implemented an end-to-end data pipeline using **AWS S3** and **Databricks**, following the **Medallion Architecture (Bronze–Silver–Gold)** to enable scalable, automated, and reliable data processing.

The pipeline is event-driven: whenever new CSV files are uploaded to S3, the system automatically triggers a Databricks job to ingest, transform, and deliver analytics-ready data.

## ⚙️ Architecture & Workflow

1. **Data Ingestion (Bronze Layer)**
  - Automatically ingests raw CSV data from S3
  - Preserves original data schema for traceability and auditing
2. **Data Cleaning & Transformation (Silver Layer)**
  - Standardizes formats (e.g., timestamp normalization)
  - Removes invalid, null, and anomalous records
  - Ensures data consistency and quality
3. **Business Aggregation (Gold Layer)**
  - Builds curated datasets from cleaned data
  - Computes key business metrics for downstream analytics and dashboards

## 🔄 Automation & Orchestration

- Configured Databricks Jobs to **auto-trigger pipeline execution** upon new file arrival in S3
- Achieved **fully automated, event-driven ETL workflow**
- Reduced manual intervention and improved data freshness

## 🧰 Tech Stack

- **Cloud Storage**: AWS S3 (AWS Free Tier)
- **Data Platform**: Databricks (Free Edition)
- **Processing**: ETL Pipelines, Data Cleaning, Aggregation
- **Orchestration**: Databricks Jobs

## 💡 Key Highlights

- Implemented **Medallion Architecture (Bronze–Silver–Gold)** for scalable data modeling
- Built an **automated data pipeline** triggered by real-time data ingestion
- Demonstrated **end-to-end ownership**: from ingestion → transformation → business metrics


## 📌 Dataset Source

**ETL Pipeline Workflow.ipynb**

Integrates the complete end-to-end Medallion ETL code across Bronze, Silver and Gold layers.

## 👤 Author - Zixuan Zhang

This portfolio project demonstrates my proficiency in designing and building automated ETL pipelines with Databricks — a core skill set essential for Data Analyst and Data Engineering roles.

- **LinkedIn**: [My Professional Profile](https://www.linkedin.com/in/zixuan-zhang-78ba38274)
