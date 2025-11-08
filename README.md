# 🩺 Medical Imaging Analysis System

This project is a **deep learning–based application** for analyzing **chest X-ray images**.  
It uses a **Flask backend** (`app.py`) and a **Jupyter notebook** (`main_notebook.ipynb`) to perform both **segmentation** and **classification** of lung diseases.

---

## ⚙️ Overview
- **U-Net**: Segments and highlights abnormal regions in the X-ray.  
- **ResNet-50**: Classifies the image into possible chest pathologies.  
- **Flask App**: Provides a simple web interface to upload and analyze images.  

---

## 🧩 Files
| File | Description |
|------|--------------|
| `app.py` | Flask web app that loads trained models and serves predictions. |
| `main_notebook.ipynb` | Notebook for training, preprocessing, and testing the models. |
| `README.md` | Project documentation. |

---

## ▶️ Run the App
1. Install dependencies:
   ```bash
   pip install Flask tensorflow opencv-python numpy scikit-learn


2. Run the Flask app:

   ```bash
   python app.py
   ```
3. Open your browser at:

   ```
   http://127.0.0.1:5000/
   ```

---

## 🧠 Technologies

* Python
* TensorFlow / Keras
* OpenCV
* Flask
* NumPy, scikit-learn

