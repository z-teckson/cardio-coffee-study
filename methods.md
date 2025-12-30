# Methodology

## Data Sources
- Hypothetical public dataset containing anonymized patient records, including daily coffee intake (in cups) and incidence of cardiovascular events over a 10-year period.

## Data Cleaning Steps
1. Load raw dataset from CSV file.
2. Handle missing values: median imputation for numerical variables, 'missing' category for categorical variables.
3. Convert data types as needed.
4. Export cleaned dataset for analysis.

## Statistical Analysis
- Cox proportional hazards regression to model time-to-event data.
- Coffee consumption as primary predictor.
- Adjust for potential confounders: age, sex, smoking status, BMI.