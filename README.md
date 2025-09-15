# 🛍️ Retail Sales Forecasting & Anomaly Detection

## 🔹 Overview
Developed an end-to-end solution to forecast weekly retail sales and detect anomalies using Python’s Prophet model and SQL queries.  
Built Tableau and Google Sheets dashboards for real-time sales monitoring and demand planning.

## 🔹 Dataset
- Source: [Kaggle - Store Item Demand Forecasting Challenge](https://www.kaggle.com/competitions/demand-forecasting-kernels-only/data)
- 145,000+ records of daily sales across 10 stores and 50 items (2013–2017).

## 🔹 Methodology
1. **Data Preprocessing**: Cleaned & aggregated daily sales to weekly data.  
2. **Forecasting**: Applied Prophet for 26-week forecasting.  
3. **Evaluation**: Achieved **MAPE = 2.62%** (~97.4% forecast accuracy).  
4. **Anomaly Detection**:  
   - Isolation Forest (ML-based)  
   - SQL-based anomaly queries to detect holiday-driven demand spikes & stockouts.  
5. **Visualization**: Exported results into Tableau & Google Sheets dashboards.

## 🔹 Results
- Forecasted sales with **±3% error**.  
- Identified seasonal anomalies (Diwali, Christmas, New Year spikes).  
- Built real-time dashboard for actionable insights.  

## 🔹 Tech Stack
- Python (Pandas, Prophet, Scikit-learn)  
- SQL (Anomaly Detection Queries)  
- Tableau, Google Sheets  
- Jupyter/Colab  

## 🔹 Example Visualizations
📊 (Add screenshots of forecast plot + Tableau dashboard here)

## 🔹 How to Run
```bash
pip install -r requirements.txt
jupyter notebook retail_forecast.ipynb
