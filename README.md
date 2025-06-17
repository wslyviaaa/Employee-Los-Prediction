
# Forecasting Employee Retention

This project predicts employee retention using various machine learning models. It is implemented in Google Colab and structured for full reproducibility.

# 📄 Dataset
File Name: FACTDATA_SEPT2024.TXT

Source: U.S. Office of Personnel Management (OPM) (https://www.opm.gov)  

This dataset was downloaded from the official OPM website and contains federal employee data as of September 2024. It is used in this project for analysis and forecasting employee retention trends.

## 📊 Exploratory Data Analysis (EDA)

The initial EDA was conducted separately and is not included as code in this notebook. However, a detailed report summarizing the EDA findings is available at https://docs.google.com/document/d/1G2toOvQCGtXRdchzsnqAkdkQn3cSf-fpi44q3G0BSSo/edit?usp=sharing 

## 📂 Project Structure for Data Modelling and Deployment

- **Part 1:** File Upload
- **Part 2:** Dataset Information
- **Part 3:** Data Cleaning
- **Part 4:** Choosing Features
- **Part 5:** Feature Engineering
- **Part 6:** Correlation
- **Part 7:** Modelling (Linear Regression, Random Forest, KNN, Gradient Boosting)
- **Part 8:** Compare and Save Models

## 📎 How to Reproduce

1. Open the Colab notebook:  
   📎 [Google Colab Link](https://colab.research.google.com/drive/1vfBgonzOf-xcQLofh5xG4RRkh0z5RR9r?usp=sharing#scrollTo=4BxCLFq4BT1L)
2. Upload the dataset file: `FACTDATA_SEPT2024.TXT`
3. Run all cells from top to bottom
4. (Optional) Download trained models and visualizations

## 🧪 Requirements

pandas: 2.2.2
numpy: 2.0.2
seaborn: 0.13.2
matplotlib: 3.10.0
scikit-learn: 1.6.1
joblib: 1.5.1
```

## 📤 Outputs

- Trained models (e.g., `rf_model.joblib`)
- Visualizations (correlation heatmap, accuracy plots)
- Feature-engineered datasets

✅ Reproducibility Notes
All random seeds are fixed for consistent results.

File paths are dynamic (support for both upload and Drive).

Environment dependencies are listed and exportable.