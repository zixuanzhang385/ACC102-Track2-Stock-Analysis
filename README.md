# ACC102-Track2-Stock-Analysis
Python Financial Analysis Project

## Project Overview
This tool solves the gap between complex professional financial valuation tools and ordinary non-professional investors.
It provides easy-to-understand stock scoring and investment recommendation results.

## Supported Industry Categories
1. Financial & Banking Industry
2. Traditional Heavy-asset Industry
3. Technology Light-asset Industry

## Input Financial Indicators
- P/E Ratio
- P/B Ratio
- Revenue Growth Rate
- ROE (Return on Equity)
- Dividend Yield

## Python Functions Used
- `input()` & `float()`: Data input and validity verification
- `if-else` logic: Differentiated scoring for different industries
- `print_slow()`: Smooth text output animation
- `draw_radar_chart()`: 5-dimensional data visualization
- `numpy & matplotlib`: Radar chart drawing and data processing

## Program Output Results
1. Comprehensive stock score (0-100 full score)
2. Final investment level: Strong Buy / Buy / Hold
3. Multi-dimensional performance radar chart

## How To Run
1. Install dependent libraries: `numpy`、`matplotlib`
2. Open and run the Python code file
3. Select the corresponding industry number according to prompts
4. Enter the stock financial data as required
5. Automatically calculate score, output verdict and generate radar chart

## Project Limitations
- Relies on manual user input data
- Adopts fixed rule-based scoring standard
- Does not include market sentiment and news analysis

## Future Optimization
- Automatically obtain real-time stock financial data
- Introduce machine learning prediction model
- Expand more industry valuation judgment standards
