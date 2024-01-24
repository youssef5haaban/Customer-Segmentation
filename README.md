# Customer Segmentation

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Overview

Customer Segmentation is a project focused on understanding customer behavior, targeting the right demographics, and delivering value efficiently. The project utilizes RFM (Recency, Frequency, Monetary) analysis for segmentation and pattern identification. Customers are categorized, validated with k-means clustering, and machine learning is integrated for refined segmentation and targeted strategies.

## Project Highlights

- **RFM Analysis:** Utilized RFM analysis to create an RFM score for each customer, identifying patterns and detecting the most valuable clients.

- **Manual Segmentation:** Segmented customers into nine distinct categories representing varying degrees of customer loyalty or risk of churn based on the RFM scores.

- **K-means Clustering:** Applied k-means clustering to the RFM scores, determining the optimal number of clusters using the elbow method and silhouette analysis.

- **Integration of Machine Learning:** Integrated machine learning with traditional RFM analysis, effectively refining the customer segmentation process and driving targeted strategies.

## Implementation Details

### Tools Used

- Sklearn
- Plotly
- Matplotlib

### Methodology

1. **RFM Analysis:** Created an RFM score for each customer based on recency, frequency, and monetary values.

2. **Manual Segmentation:** Segmented customers into nine distinct categories based on the RFM scores.

3. **K-means Clustering:** Applied k-means clustering to the RFM scores, determining the optimal number of clusters through the elbow method and silhouette analysis.

4. **Integration of Machine Learning:** Integrated machine learning with traditional RFM analysis, aligning with the manual segmentation for validation.

## Dataset

- `Online Retail.xlsx`: The dataset used for the project.

## Summary and Conclusion

To better understand customer behavior, the project combined RFM analysis and K-means clustering on the "Online Retail" dataset spanning from 2010 to 2011. The analysis revealed three distinct customer segments: Lost Customers, At-Risk Customers, and Top Customers. This segmentation provides valuable insights into the customer base, aiding in targeted marketing and improving customer relationship management.

The combined approach of using RFM and K-means clustering brings together the simplicity of RFM with the objective and detailed nature of K-means clustering. The insights gained from this analysis can inform tailored marketing strategies, re-engagement efforts for Lost and At-risk customers, and the maintenance of loyalty among Top customers.

This project demonstrates the power of data analysis in helping a business understand its customers better and make more informed decisions.

## Usage

1. Open and explore the `final.ipynb` notebook for detailed project information.
2. Analyze the customer segmentation results obtained from RFM analysis and K-means clustering.
3. Utilize the insights gained to inform targeted marketing strategies and customer relationship management.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
