# 📊 Layoffs  SQL

This project explores a global dataset of layoffs across different companies, industries, countries, and funding stages. Using SQL, I performed exploratory data analysis (EDA) to uncover key trends, identify patterns, and draw actionable insights.

## 🛠 Tools & Technologies
- SQL (MySQL / PostgreSQL syntax compatible)
- Data cleaning and transformation
- Window functions, CTEs, aggregations

## 🔍 Key Insights
- Identified companies that laid off 100% of their workforce — mostly early-stage startups.
- Discovered that some well-funded companies (e.g., Quibi, BritishVolt) went under despite raising billions.
- Analyzed layoffs by year, country, industry, and stage to understand the broader trends.
- Created rolling total of layoffs per month to visualize the impact over time.
- Ranked companies with highest layoffs per year using advanced window functions.

## 📁 Dataset
- `layoffs_staging2`: Cleaned and preprocessed version of the original dataset.

## 📈 Example Queries
- Total layoffs by company, country, and year
- Companies with the highest percentage of workforce laid off
- Monthly and cumulative trends using `OVER()` and `CTEs`
- Top companies by layoffs per year using `DENSE_RANK()`

## 📎 How to Use
1. Load the dataset into your SQL environment (e.g., MySQL, PostgreSQL).
2. Run the queries from the notebook or SQL script provided.
3. Customize or expand the analysis based on your interests (e.g., filtering by industry or funding stage).



