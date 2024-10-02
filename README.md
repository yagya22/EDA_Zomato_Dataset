# Zomato Bangalore Data Analysis
EDA for restaurant data in Bangalore using the Zomato dataset from Kaggle. The project aims to extract insights regarding restaurant locations, customer preferences, and trends in online ordering and table booking.

**Dataset Link** https://www.kaggle.com/datasets/rajeshrampure/zomato-dataset

## Dataset Overview
The dataset includes:
- **Location & Restaurant Names:** Popular areas in Bangalore (e.g., Koramangala, Indiranagar) and restaurant chains.
- **Ratings & Votes:** Customer feedback in terms of `rate` and `votes`.
- **Services:** Details on `online_order` availability and `book_table` status.

## Analysis  & Findings
### 1. Online Ordering & Table Booking
- **Visualization:** Pie charts for restaurants offering online orders and allowing table booking.
- **Insight:** ~70% of restaurants offer online orders, and a smaller percentage offer table bookings.

### 2. Ratings & Locations
- **Analysis:** Grouped by `location` to find average ratings.
- **Finding:** Koramangala and BTM are popular, with varying average ratings.

### 3. Restaurant Type & Cost
- **Exploration:** Distribution of restaurant types (`rest_type`) and their `approx_cost`.
- **Observation:** Most restaurants are casual dining, with costs varying significantly.

## Visualizations & Plots
- **Pie Charts:** Top 10 locations based on outlet counts.
- **Bar Plots:** Ratings by location, showing popular areas and their restaurant density.

##Tools & Libraries
- **Pandas** for data manipulation
- **Matplotlib** for visualization
- **NumPy** for numerical computations
  
