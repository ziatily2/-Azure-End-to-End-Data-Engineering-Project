# 🚀 Azure End-to-End Data Engineering Project: AdventureWorks

## 📌 Project Overview
This project implements an **end-to-end data engineering pipeline** using **Microsoft Azure** for processing and analyzing AdventureWorks data. It leverages **Azure Data Factory, Synapse Analytics, Databricks, and Data Lake Storage** to handle data ingestion, transformation, and querying.

## 🏗️ Architecture
### **1️⃣ Data Ingestion (Bronze Layer)**
- **Source**: GitHub (CSV files)
- **Tool**: Azure Data Factory
- **Storage**: Azure Data Lake (Bronze layer)
- **Process**: Ingest raw CSV files from GitHub and store them in **Azure Data Lake**.

### **2️⃣ Data Processing (Silver Layer)**
- **Tool**: Azure Databricks (PySpark)
- **Process**:
  - Cleanse and transform the raw data.
  - Store the processed data in the **Silver layer** of Azure Data Lake.

### **3️⃣ Data Aggregation (Gold Layer)**
- **Tool**: Azure Databricks (PySpark)
- **Process**:
  - Perform advanced transformations and aggregations.
  - Store curated data in the **Gold layer** for analytics.

### **4️⃣ Data Analytics (Azure Synapse Analytics)**
- **External tables** are created in **Synapse Analytics** to enable querying and visualization.
- **Query execution** for reporting and insights.

## 🛠️ Tech Stack
- **Azure Data Factory** - Orchestrating data ingestion
- **Azure Databricks** - Processing & transforming data (PySpark)
- **Azure Data Lake Storage** - Storing raw, processed, and curated data
- **Azure Synapse Analytics** - Querying and reporting
- **SQL** & **PySpark** - Data transformations



## 🚀 How to Run the Project
1. **Clone the Repository**
   ```bash
   git clone https://github.com/ziatily2/Azure-End-to-End-Data-Engineering-Project.git
   cd Azure-End-to-End-Data-Engineering-Project
   ```
2. **Set up Azure Resources**
   - Create an **Azure Data Lake Storage account**
   - Configure **Azure Data Factory** for data ingestion
   - Set up **Azure Databricks** for data transformation
   - Create an **Azure Synapse Analytics workspace**

3. **Execute Pipelines**
   - Run **Data Factory pipelines** to ingest raw data.
   - Execute **Databricks notebooks** to process and clean data.
   - Load transformed data into **Synapse Analytics**.
   - Query data using **SQL scripts**.

## 📊 Visualizations
For better insights, Power BI can be connected to Azure Synapse Analytics for dashboarding and reporting.

## 📌 Future Enhancements
- Implement **incremental data ingestion**.
- Automate workflows using **Azure Logic Apps**.
- Enhance visualization with **Power BI dashboards**.





