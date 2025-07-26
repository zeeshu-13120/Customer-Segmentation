
# 🛍️ Customer Segmentation Project

This project focuses on segmenting mall customers into distinct groups based on their **Annual Income** and **Spending Score** using **K-Means** and **DBSCAN** clustering algorithms. The goal is to identify customer behavior patterns that can help businesses develop more targeted and effective marketing strategies.

---

## 📌 Project Overview

The workflow followed in this project includes:

- **📊 Data Exploration & Preprocessing**  
  Understand the dataset, clean missing values, and prepare for analysis.

- **🧠 Clustering Model Development**  
  Apply **K-Means** and **DBSCAN** to identify customer segments.

- **📈 Model Evaluation & Interpretation**  
  Determine the optimal number of clusters using metrics and visualize clusters.

- **🔍 Advanced Exploration**  
  Perform deeper analysis using DBSCAN and analyze cluster-based spending patterns.

- **🖼️ Visualization**  
  Create clear plots to represent and understand customer groupings.

---

## 🧰 Technologies & Libraries Used

- **Python 3.12.10**
- **Jupyter Notebook**

### 📦 Python Libraries

- `pandas` – Data manipulation
- `numpy` – Numerical operations
- `matplotlib` – Basic visualizations
- `seaborn` – Statistical plots
- `scikit-learn` – Clustering algorithms and preprocessing tools

---

## ⚙️ Installation & Setup

### 1. Clone the Repository & Download Dataset

Create a folder and use the dataset in the directory:

```bash
mkdir CustomerSegmentationProject
cd CustomerSegmentationProject
```

Use the downloaded `Mall_Customers.csv`.

---

### 2. Set Up Virtual Environment (Recommended)

```bash
# Create virtual environment
python -m venv venv

# Activate on Windows
.env\Scripts activate

# Activate on macOS/Linux
source venv/bin/activate
```

---

### 3. Install Dependencies

Intall `requirements.txt` file with:

```bash
pip install -r requirements.txt
```

---

### 4. Launch the Project

```bash
jupyter-lab
```

- Open `Customer_Segmentation.ipynb`.
- Run all cells to execute the workflow and view analysis results.

---

## 📂 Project Structure

```
CustomerSegmentationProject/
├── Mall_Customers.csv                   # Dataset
├── Customer_Segmentation.ipynb          # Main notebook
├── requirements.txt                     # Required Python libraries
├── ProjectReport_Zeeshan.pdf            # Optional in-depth report
└── README.md                            # Project documentation
```

---

## ▶️ Usage

1. Run JupyterLab: `jupyter-lab`
2. Open `Customer_Segmentation.ipynb`
3. Run each cell sequentially to:
   - Explore and clean the data
   - Apply clustering algorithms
   - Visualize customer segments

---

## 🤝 Contributing

Contributions are welcome!

If you have suggestions or improvements, feel free to:

- Fork the repo
- Create a new branch
- Submit a Pull Request

For major changes, open an issue first to discuss proposed updates.

---

## 📄 License

This project is licensed under the **[Unlicense](https://unlicense.org/)** — free to use, modify, and distribute for any purpose.

---

> Made with 💡 for practicing unsupervised machine learning and customer analytics.
