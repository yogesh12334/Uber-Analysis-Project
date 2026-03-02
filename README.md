Uber Ride Data Analytics Dashboard 🚖
📌 Project Overview
This repository contains an end-to-end Uber Data Analytics project. The goal of this project is to analyze ride-hailing data to extract actionable insights regarding revenue trends, vehicle performance, and customer behavior.

Using Power BI, I transformed raw data into an interactive multi-page dashboard that helps stakeholders monitor business health and identify areas for operational improvement.

🛠️ Tech Stack & Skills
Data Visualization: Power BI Desktop

Data Cleaning & ETL: Power Query (M Language)

Data Modeling: Star Schema / Snowflake Schema

Analytics: DAX (Data Analysis Expressions) for complex measures and KPIs

UI/UX: Navigation buttons and consistent branding for professional look

📊 Dashboard Features & Pages
The dashboard consists of 7 specialized pages for granular analysis:

Home Page: A sleek landing page with navigation buttons to all report sections.

Overview: High-level KPIs including Total Revenue ($52M), Completed Rides (93K), and Avg Distance (24.64).

Vehicle Analysis: Comparative study of vehicle types (Auto, Bike, Premier Sedan, etc.) based on booking count and revenue contribution.

Revenue Insights: Analysis of revenue by Payment Methods (UPI, Cash, Wallet) and monthly/quarterly trends.

Rider Details: Deep dive into customer booking values, loss booking analysis, and cancellation reasons.

Location & Timing: Heatmaps and matrices showing Peak Booking Hours and top pickup/drop locations like Khandsa and Ashram.

Summary Chart: Detailed tabular and graphical view of all metrics across vehicle categories.

🧹 Data Cleaning Process
Before visualization, I performed the following tasks in Power Query:

Handling Nulls: Managed missing values in cancellation reasons and ride distances.

Data Formatting: Standardized date/time columns for time-series analysis.

Custom Columns: Created calculated columns to categorize ride status (Completed, Cancelled, Incomplete).

Measure Creation: Developed DAX measures for calculating Cont% (Contribution Percentage) and Lost Booking counts.

💡 Key Insights
Revenue Leader: The Auto and Bike categories contribute significantly to the total booking volume.

Cancellations: A high number of 'Lost Bookings' (57K) were identified, with specific insights into whether the driver or customer initiated the cancellation.

Peak Demand: Most bookings occur during specific morning and evening slots, as visualized in the Time-Slot matrix.

Preferred Payment: UPI is the most utilized payment method, followed by Cash.

🚀 How to Run
Clone this repository.

Ensure you have Power BI Desktop installed.

Open the Uber_Analytics.pbix file.

(Optional) The raw dataset is provided in the Data folder if you wish to perform your own transformations.


<img width="1318" height="734" alt="image" src="https://github.com/user-attachments/assets/13c2d2a4-595e-4033-9aef-f54b4167ad40" />

