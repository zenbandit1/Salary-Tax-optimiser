# UK Family Business Tax Calculator

An interactive, browser-based tax calculator for UK family business owners to optimize salary and dividend strategies across multiple family members.

## Features

- **Multi-Employee Tax Planning**: Calculate optimal salary and dividend strategies for multiple family members
- **Tax Year Selection**: Choose between 2024/25 and 2025/26 tax years with accurate rates and thresholds
- **Employer's Allowance Support**: Apply Employer NI allowance (£5,000 in 2024/25, £10,500 in 2025/26)
- **Visual Analysis**: See cost breakdown with interactive charts
- **Detailed Tax Calculation**: Shows income tax, NI, dividend tax, and corporation tax impacts
- **Comparison Mode**: Compare tax efficiency across different salary levels

## How to Use

1. Simply open `Salary_Calc_v1_multi_staff_Ni_ers.html` in any modern web browser
2. Enter your company's bottom line profit
3. Add family members with their respective salaries, tax codes, and dividend amounts
4. Select whether to apply the Employer's Allowance
5. Click "Calculate Family Business Tax" to see results
6. Use the comparison tab to explore different salary levels

## Calculations

The calculator provides detailed breakdowns of:

- Take Home Pay = Gross Salary + Dividend - Income Tax - Dividend Tax - Employee NI
- Total Cost to Company = Gross Salary + Dividend + (Employer NI after Allowance) - Corporation Tax Savings
- Corporation Tax Savings = (Salary + Employer NI) × Corporation Tax Rate
- Net Position = Corporation Tax Savings - (Income Tax + Dividend Tax + Employee NI + Employer NI after Allowance)

## Tax Rates

The calculator includes up-to-date tax rates for:
- Income Tax (Basic, Higher, and Additional rates)
- National Insurance (Employee and Employer)
- Corporation Tax
- Dividend Tax rates
- Various thresholds and allowances

## Technical Details

- Built with HTML, CSS, and JavaScript
- Uses Chart.js for visualizations
- Runs entirely in the browser with no server requirements
- No external dependencies other than Chart.js (loaded via CDN)

## License

This project is provided for educational purposes only. Please consult with a qualified tax professional before making any tax decisions based on these calculations.