# 460 Assignment 2 - Project Scheduling and Analysis

## Overview
This repository contains files related to **Project Scheduling and Uncertainty Analysis** for **460 Assignment 2**. The assignment involves:
- Developing a **linear programming model** for project scheduling.
- Implementing **Monte Carlo simulation** to handle uncertainty in task completion.
- Generating **Gantt charts** and identifying the **critical path** for different scenarios.

## Files in This Repository

### **1. `460_assignment2.py`**
- **Main Python script** implementing:
  - **Linear Programming Model** for project scheduling.
  - **Critical Path Analysis**.
  - **Gantt Chart Generation**.
  - **Monte Carlo Simulation** for uncertainty handling.
- Uses **Pandas, NetworkX, Matplotlib, NumPy, and SciPy** for analysis and visualization.

### **2. `460_assignment2_Cleared_Output.py`**
- A **cleaned version** of the main script with **no execution output**.
- Useful for running the script **from scratch** without pre-generated results.

### **3. `460_Assignment2_WriteUp.pdf`**
- Detailed **write-up** describing:
  - **Methodology** for scheduling and uncertainty modeling.
  - **Results from Monte Carlo simulation** and **critical path analysis**.
  - **Key takeaways and recommendations**.

### **4. `LICENSE` (MIT)**
- MIT License for open-source use and modifications.

## **How to Run the Code**
### **Prerequisites**
Ensure you have **Python 3.8+** installed with the following libraries:
```bash
pip install pandas networkx matplotlib numpy scipy pulp
