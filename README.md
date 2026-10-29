# Agricultural Market Price Volatility Analysis

## Project Overview
This Power BI project analyzes agricultural farm and retail prices to understand price differences, market spreads, city-level retail pricing, and farm price volatility. The interactive executive dashboard presents key performance indicators (KPIs) and visualizations to support data-driven market analysis.

## Objectives
- Compare average farm prices with retail prices across four cities.
- Analyze differences between farm and retail prices.
- Examine average price spreads across agricultural products.
- Measure farm price variability using statistical indicators.
- Present key findings through an executive Power BI dashboard.

## Tools & Technologies
- **Microsoft Power BI Desktop** — dashboard development and data visualization
- **DAX** — KPI calculations and analytical measures
- **Power Query** — data cleaning and transformation
- **CSV** — source dataset

## Dataset
**File:** `ProductPriceIndex.csv`

The dataset contains agricultural product prices and price-spread information, including:
- Product name
- Date
- Farm price
- Retail prices in Atlanta, Chicago, Los Angeles, and New York
- Average price spread

Data preparation included cleaning currency and percentage symbols, converting columns to appropriate data types, and checking for missing values and duplicate product-date combinations.

## Key Performance Indicators (KPIs)
1. **Average Farm Price** — average recorded farm price.
2. **Average Retail Price** — mean of the four cities' average retail prices.
3. **Average Price Spread (%)** — average recorded price spread expressed as a percentage.
4. **Average Absolute Price Gap** — average absolute difference between farm prices and retail prices across the four cities.
5. **Farm Price Volatility (%)** — farm-price standard deviation relative to its average price.
6. **Products Analyzed** — number of distinct agricultural products.

## Dashboard Visualizations
1. Average Retail Price by City — Top 4
2. Average Farm Price by Product — Top 4
3. Average Price Spread by Product — Top 10
4. Farm Price Volatility by Product — Top 4

## Repository Contents
| File | Description |
|---|---|
| `AMPV1.pbix` | Power BI report file |
| `Executive_Dashboard.png` | Executive dashboard screenshot |
| `ProductPriceIndex.csv` | Source dataset |
| `KPI_Calculations.docx` | KPI formulas and explanations |
| `Recommendation_Justification.docx` | Supporting justifications for recommendations |
| `.gitignore` | Files and patterns excluded from Git tracking |

## How to Use
1. Download or clone this repository.
2. Open `AMPV1.pbix` using Power BI Desktop.
3. If prompted, update the source-data path to `ProductPriceIndex.csv`.
4. Refresh the data if required.
5. Explore the dashboard KPIs and visualizations.

## Business Value
The dashboard helps users compare farm and retail pricing, identify products with larger price spreads, examine differences across retail markets, and assess farm-price variability. These insights can support further investigation into agricultural pricing patterns.

## Limitations
- The findings depend on the coverage, quality, and time range of the supplied dataset.
- Price differences alone do not establish their causes.
- Farm-price volatility is measured using the coefficient of variation; it indicates relative variability rather than forecasting future prices.
- Missing values and zero prices should be considered when interpreting individual results.

## Author
**Yash Srivastava**

## Disclaimer
This project is intended for educational and analytical portfolio purposes. The results describe patterns in the available dataset and should not be interpreted as proof of market causation or as financial advice.