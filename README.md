# ESG_Thailand_Financial_Performance
README
Dataset Title: ESG Performance and Financial Indicators of Thai Listed Companies (2020–2024)
1. Overview
This dataset contains firm-level panel data used to examine the relationship between Environmental, Social, and Governance (ESG) performance and financial performance of publicly listed companies in Thailand. The data support the empirical analysis presented in the associated research article submitted to Forecasting and are intended for academic research, replication, and further analysis.
The dataset covers multiple industries and spans five fiscal years (2020–2024), allowing both cross-sectional and longitudinal analyses of ESG–financial performance dynamics in an emerging market context.
2. File Description
•	File name: Thailand_ESG__data_30102025.csv
•	File format: Comma-Separated Values (CSV)
•	Encoding: UTF-8
•	Unit of observation: Firm–year
•	Total observations: 965 firm-year records
Each row represents one firm in one fiscal year.
3. Dataset Structure
3.1 Key Variables
Variable Name	Description	Measurement / Scale
Firm_ID	Unique identifier for each listed company	Nominal
Year	Fiscal year of observation	Integer (2020–2024)
ROCE	Return on Capital Employed	EBIT / Capital Employed
ROA	Return on Assets	Net Income / Total Assets
ESG	Composite ESG performance score	1 (Very Poor) – 5 (Excellent)
SIZE	Firm size	Natural logarithm of total assets
LEVERAGE	Financial leverage	Total liabilities / Total assets
3.2 ESG Score Construction
The ESG score is a composite index constructed following the CRISIL ESG Scoring Methodology (2023):
[
ESG = (0.35 \times Environmental) + (0.25 \times Social) + (0.40 \times Governance)
]
•	Environmental, Social, and Governance pillar scores are each rated on a five-point scale.
•	A higher score indicates stronger sustainability performance.
•	Governance is given the highest weight, reflecting its role as a structural enabler of ESG practices.
4. Data Sources
•	Financial data: Audited annual reports and publicly available financial statements of firms listed on the Stock Exchange of Thailand (SET).
•	ESG data: ESG ratings derived from CRISIL’s standardized ESG assessment framework.
All data sources are secondary, publicly available, and non-confidential.
5. Data Interpretation Guidelines
•	ROA and ROCE measure short-term accounting performance and capital efficiency, respectively. Negative values may occur for firms experiencing losses or financial distress.
•	ESG scores reflect relative sustainability performance and should be interpreted as ordinal-to-quasi-interval measures suitable for regression analysis.
•	SIZE is log-transformed to reduce skewness and improve comparability across firms.
•	LEVERAGE values greater than 1 indicate firms whose total liabilities exceed total assets, signaling elevated financial risk.
The dataset is unbalanced, meaning not all firms appear in every year.
6. Recommended Use
This dataset is suitable for:
•	Panel regression analysis (fixed-effects or random-effects models)
•	Granger causality testing
•	ESG–financial performance studies in emerging markets
•	Comparative or replication studies related to sustainability and forecasting
Users are encouraged to conduct diagnostic tests (e.g., stationarity, multicollinearity) prior to modeling.
7. Limitations
•	The dataset covers a short to medium time horizon (5 years) and may not capture long-term ESG effects.
•	ESG scores are aggregated and do not allow separate analysis of environmental, social, and governance pillars unless supplemented with additional data.
•	Industry-specific effects are not explicitly coded and should be controlled for externally if required.
8. Ethical Considerations
The dataset contains no personal or sensitive information. All data are derived from publicly available corporate disclosures. No ethical approval was required.
9. Citation
If you use this dataset, please cite the associated article:
Detthamrong, U.; Klangbunrueang, R.; Chansanam, W.; Dasri, R. The Impact of ESG Performance on Financial Performance: Evidence from Listed Companies in Thailand. Submitted to Forecasting.
10. Contact
For questions regarding the dataset or methodology, please contact:
Wirapong Chansanam, Ph.D.
Department of Information Science
Faculty of Humanities and Social Sciences
Khon Kaen University, Thailand
Email: wirach@kku.ac.th

