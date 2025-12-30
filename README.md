# ⚡ Ather Stock Allocation & Inventory Management System

An advanced Excel-based inventory management system designed for electric vehicle (Ather) dealerships to track vehicle stock allocation, availability, damage tracking, aging analysis, pre-bookings, and charger compatibility. This system provides complete transparency for sales teams to manage inventory efficiently and ensure accurate vehicle-charger pairing.

## 📋 Overview

This system solves critical inventory management challenges for EV dealerships: **How to track available stock, allocations, damage inventory, aging periods, pre-bookings, and ensure proper charger allocation for each vehicle model.**

The system helps dealerships and sales teams by:
- **Real-Time Stock Visibility**: View free stock by color and model (450 X)
- **Allocation Tracking**: Monitor which vehicles are allocated, held, or available
- **Damage Stock Management**: Transparent tracking of damaged inventory
- **Aging Analysis**: Track how long vehicles remain in inventory
- **Pre-Booking Management**: Link salespeople to customer pre-bookings
- **Charger Compatibility**: Ensure correct charger allocation per vehicle model
- **Location Tracking**: Know where each vehicle is located in the dealership

## 📸 View & Play with the File

**[Access Ather Stock Allocation System](https://docs.google.com/spreadsheets/d/1_MPsV5xK9Pgx_FmYz1DfumbP07w7B4z7Fs9Ta3IR_KM/edit?sharingaction=ownershiptransfer&gid=2102566362#gid=2102566362)**

> Click the link above to access and explore the live inventory system

## 📊 System Screenshots

### Allocation Report Dashboard
<img width="1085" height="608" alt="image" src="https://github.com/user-attachments/assets/b620c30c-7dfb-499c-9b12-cc2a5105ce7c" />

*View free stock by color and model, allocation status, and pending allocations at a glance*

### Allocations Data - Detailed Vehicle Tracking
<img width="1359" height="606" alt="image" src="https://github.com/user-attachments/assets/c5e6d908-4bba-4405-a7b8-e58fb2626628" />

*Detailed vehicle-level tracking including PO numbers, chassis numbers, charger allocation, and aging analysis*

### Charger Allocation Matrix
<img width="1355" height="603" alt="image" src="https://github.com/user-attachments/assets/ff3972b0-8fff-4d5b-84b4-9327b94b4746" />

*Charger allocation details with customer information and dealership assignments*

## ✨ Features

### 1. Stock Allocation Report (Main Dashboard)
- **Free Stock Summary**: Total available vehicles by color and model
- **Allocation Status**: Track allocated, held, and available inventory
- **Color-wise Breakdown**: Visual representation of stock by color (450 X models)
- **Hold Reasons**: Transparent tracking of why vehicles are on hold
- **Damage Stock Visibility**: Separate tracking of damaged inventory

### 2. Allocation Data (Detailed Tracking)
Complete vehicle lifecycle tracking:
- **PO/Invoice Details**: Source invoice number for each vehicle
- **Vehicle Information**: Model number, AC number, specifications
- **Charger Assignment**: Charger number allocated to each vehicle
- **Location Tracking**: Physical location within dealership
- **Allocation Date**: When vehicle was allocated to customer
- **Salesperson Assignment**: Who is responsible for the sale

### 3. Aging Analysis
Track inventory holding periods:
- **Order Date**: When vehicle was ordered from manufacturer
- **Arrival Date**: When vehicle reached showroom
- **Days Pending**: How many days vehicle has been in inventory
- **Aging Period**: Time since arrival without allocation
- **Follow-up Alerts**: Identify long-pending stock requiring action

### 4. Pre-Booking Management
- **Customer Details**: Name and contact information
- **Salesperson Assignment**: Who booked the customer
- **Preferred Model/Color**: Customer preferences recorded
- **Booking Status**: Track from booking to allocation
- **Easy Lookup**: Quickly find if allocation has been completed

### 5. Charger Allocation System
Critical for EV dealerships:
- **Model-Specific Chargers**: Different chargers for different Ather models
- **Charger Compatibility Tracking**: Ensure correct charger-vehicle pairing
- **Charger Number Mapping**: Link specific charger to vehicle AC number
- **Allocation Verification**: Prevent delivery without proper charger
- **Charger Availability**: Track charger inventory separately

### 6. Multi-View Analysis
- **Project-wise View**: Stock allocation by project/location
- **PSI Analysis**: Performance Service Index tracking
- **Month-wise Tracking**: Temporal analysis of allocations
- **Consolidated Reports**: All data merged for complete visibility

## 🎯 Business Problems Solved

### The Challenge:
- Sales teams couldn't easily identify available stock by color and model
- No visibility into why vehicles were on hold
- Damage stock was not tracked transparently
- Long-pending inventory wasn't identified for follow-up
- Risk of delivering vehicles with wrong chargers (incompatible models)
- Pre-bookings were difficult to match with arriving stock
- No clear view of vehicle location within dealership
- Aging analysis required manual calculation

### The Solution:
✅ **Instant Stock Visibility** - Color and model-wise free stock at a glance  
✅ **Transparent Hold Tracking** - Clear reasons for held inventory  
✅ **Damage Stock Management** - Separate tracking with full transparency  
✅ **Automated Aging Analysis** - Days pending calculated automatically  
✅ **Charger Compatibility System** - Prevents wrong charger allocation  
✅ **Pre-Booking Integration** - Easy matching of bookings to stock  
✅ **Location Tracking** - Know where each vehicle is physically located  
✅ **Comprehensive Reporting** - All data consolidated in one system  

## 📊 Technical Implementation

**Technology Stack:**
- Microsoft Excel / Google Sheets (Advanced formulas)
- SUMIFS for color and model-wise stock counting
- VLOOKUP/XLOOKUP for charger-vehicle matching
- DATEDIF for aging period calculation
- Conditional formatting for visual stock status
- Data validation for consistent data entry
- PIVOT TABLES for multi-dimensional analysis
- Complex IF statements for allocation status logic

**Data Structure:**
- **Allocation Report Sheet**: Summary dashboard with stock totals
- **Allocation Data Sheet**: Detailed vehicle-level information
- **Pre-Booking Sheet**: Customer booking records
- **Charger Allocation Sheet**: Charger compatibility matrix
- **Aging Analysis Sheet**: Time-based inventory tracking
- **Damage Stock Sheet**: Separate damaged inventory tracking

**Key Calculations:**
```excel
Free Stock = Total Stock - (Allocated + Held + Damaged)
Aging Days = TODAY() - Arrival Date
Charger Match = VLOOKUP(Model, Charger_Table, Charger_Column)
Hold Status = IF(Hold_Reason<>"", "On Hold", "Available")
```

## 🚀 Getting Started

### Prerequisites
- Microsoft Excel 2016 or later (recommended: Microsoft 365)
- Understanding of electric vehicle models (Ather 450 X variants)
- Dealership PO/Invoice numbering system knowledge

### Download & Setup
1. **[Access the system](https://docs.google.com/spreadsheets/d/1_MPsV5xK9Pgx_FmYz1DfumbP07w7B4z7Fs9Ta3IR_KM/edit?sharingaction=ownershiptransfer&gid=2102566362#gid=2102566362)**
2. Open in Microsoft Excel or Google Sheets
3. For Excel: File → Create a Copy → Download
4. Review all sheets to understand data flow

### How to Use

**Step 1: Record New Stock Arrival**
- Navigate to "Allocation Data" sheet
- Enter PO/Invoice number from supplier
- Record vehicle details (AC number, model, color)
- Note arrival date at showroom
- Select physical location in dealership

**Step 2: Allocate Charger**
- Check "Charger Allocation" sheet for model compatibility
- Assign appropriate charger number to vehicle
- System validates charger-model compatibility
- Record charger number in allocation data

**Step 3: Manage Pre-Bookings**
- Enter customer pre-booking details
- Assign salesperson responsible
- Note preferred model and color
- When stock arrives, match to pre-booking

**Step 4: Allocate Vehicle to Customer**
- Update allocation status in "Allocation Data"
- Link to pre-booking if applicable
- Verify charger assignment
- Mark allocation date

**Step 5: Monitor Aging Stock**
- Review "Aging Analysis" regularly
- Identify vehicles pending >30 days
- Follow up on long-pending inventory
- Take action on slow-moving models/colors

**Step 6: Track Damage Stock**
- Record damaged vehicles separately
- Note damage details and status
- Update damage resolution progress
- Keep damage stock transparent

**Step 7: View Reports**
- Check "Allocation Report" for summary
- Use filters for specific models/colors
- Analyze month-wise and project-wise data
- Generate reports for management

## 📂 File Structure

```
Ather Stock Allocation System
├── Allocation Report (Summary dashboard)
│   ├── Free stock by color and model
│   ├── Held stock with reasons
│   └── Damage stock tracking
├── Allocation Data (Detailed records)
│   ├── PO/Invoice information
│   ├── Vehicle details (AC#, Model, Color)
│   ├── Charger allocation
│   ├── Location tracking
│   └── Salesperson assignment
├── Pre-Booking (Customer bookings)
│   ├── Customer information
│   ├── Salesperson assignment
│   └── Booking status
├── Charger Allocation (Compatibility matrix)
│   ├── Model-charger mapping
│   └── Charger inventory
├── Aging Analysis (Time tracking)
│   ├── Order and arrival dates
│   ├── Days pending calculation
│   └── Follow-up alerts
└── Damage Stock (Damaged inventory)
    ├── Damage details
    └── Resolution status
```

## 📈 Key Reports & Analytics

### Stock Summary Reports:
- Total free stock by model and color
- Allocated vs. available inventory
- Held stock with reasons
- Damage stock transparency
- Location-wise stock distribution

### Aging Analysis Reports:
- Vehicles pending >7 days
- Vehicles pending >30 days
- Vehicles pending >60 days (critical)
- Average aging period by model
- Slow-moving color/model combinations

### Allocation Reports:
- Daily allocation count
- Month-wise allocation trends
- Salesperson-wise allocations
- Project-wise allocation distribution
- Pre-booking fulfillment rate

### Charger Tracking:
- Charger allocation accuracy rate
- Pending charger assignments
- Charger inventory status
- Model-charger mismatch alerts

## 💡 Key Benefits

✅ **Prevents Delivery Errors**: Ensures correct charger-vehicle matching  
✅ **Improves Cash Flow**: Identifies slow-moving inventory quickly  
✅ **Enhances Customer Service**: Fast response on stock availability  
✅ **Reduces Holding Costs**: Aging analysis drives faster action  
✅ **Complete Transparency**: All stakeholders see same data  
✅ **Eliminates Manual Work**: Automated calculations save hours  
✅ **Better Inventory Planning**: Data-driven stock ordering decisions  
✅ **Increases Sales Efficiency**: Quick pre-booking to allocation matching  

## 🔧 Customization Options

This system can be adapted for:
- Different electric vehicle brands (Ola, Bajaj, TVS)
- Multiple dealership locations
- Additional vehicle variants
- Custom hold reasons and categories
- Different charger types and specifications
- Integration with DMS systems
- Automated email alerts for aging stock
- Mobile app for real-time updates

## 📈 Future Enhancements

- [ ] Web-based dashboard (Python/Flask or React)
- [ ] Automated email alerts for aging stock >30 days
- [ ] Mobile app for sales team access
- [ ] Integration with Ather's dealer management system
- [ ] QR code scanning for vehicle tracking
- [ ] Real-time stock updates across multiple locations
- [ ] Customer portal for booking status checks
- [ ] Automated charger compatibility validation
- [ ] Power BI dashboard for executive reporting
- [ ] Predictive analytics for stock demand forecasting

## 💼 For Freelancers & Employers

**Skills Demonstrated:**
- Advanced Excel formula development (SUMIFS, VLOOKUP, DATEDIF)
- Inventory management system design
- Data analysis and business intelligence
- Complex data relationship mapping (charger-vehicle compatibility)
- Aging analysis and time-based calculations
- Multi-dimensional reporting (project, month, salesperson)
- Process automation and optimization
- Understanding of EV dealership operations
- Problem-solving for operational challenges

**Available for:**
- Custom inventory management systems
- Dealership management solutions
- Excel/Google Sheets automation
- Data analysis and visualization
- Dashboard development (Excel, Power BI, Tableau)
- Process optimization consulting
- System integration projects
- Mobile app development for inventory tracking
- Training and documentation

## 🎓 Project Highlights

This project demonstrates:
- **Industry-Specific Knowledge**: Understanding of EV dealership operations
- **Critical Thinking**: Identified charger compatibility as key risk
- **Attention to Detail**: Multiple tracking dimensions (aging, location, damage)
- **Business Impact**: Prevents costly delivery errors and reduces holding costs
- **User-Centric Design**: Built for non-technical sales teams
- **Scalable Solution**: Can expand to multiple locations and vehicle brands

## 📞 Contact

For freelance inquiries, customization requests, or questions:
- [**GitHub**](https://github.com/heysubu)
- **Email**: suubhamghadge@gmail.com
- [**LinkedIn**](https://www.linkedin.com/in/subhamghadge/)

## 📄 License

This project is available under the MIT License - feel free to use and modify for your needs.

---

### 🌟 Project Stats

![Excel](https://img.shields.io/badge/Excel-Advanced-217346?logo=microsoft-excel)
![Inventory Management](https://img.shields.io/badge/Inventory-Management-blue)
![EV Dealership](https://img.shields.io/badge/EV-Dealership-green)
![Automation](https://img.shields.io/badge/Automation-High-success)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

**⚡ Built for Electric Vehicle Dealerships - Ensuring Perfect Vehicle-Charger Match Every Time**

**⭐ If you find this useful, please star this repository!**

**💬 Have questions? Open an issue, and I'll respond promptly.**

**💼 Available for inventory management and dealership automation projects!**
