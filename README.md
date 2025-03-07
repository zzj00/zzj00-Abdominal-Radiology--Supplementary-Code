# JiaJY-Abdominal-Radiology--Supplementary-Code
Deep Learning Model for Medical Imaging Based on CrossFormer
This project aims to utilize the CrossFormer architecture to construct deep learning models for T2-weighted imaging (T2WI) and Diffusion-weighted imaging (DWI) and extract relevant deep learning features. Additionally, we employ an attention mechanism-based Transformer feature fusion module to capture spatial interactions between different sequences, enabling the development of a multi-parameter fusion model to enhance medical image analysis accuracy.

📌 Project Overview
This repository primarily includes the following components:
Deep learning model construction and training: Building and extracting features from T2WI and DWI images using CrossFormer.
Self-attention feature fusion model: Utilizing the Transformer module to integrate multi-sequence imaging data and improve analysis performance.
This project is technically supported by the onekey platform.

👤 Code Structure
📂 project_root
│── 📂 code                  # Code directory
│   ├── Step0.list.ipynb         # Data listing and preprocessing
│   ├── Step1.DL_train.ipynb     # Deep learning model training
│   ├── Step2.Grad-CAM.ipynb     # Grad-CAM visualization
│   ├── Step3.DL_feature.ipynb   # Deep learning feature extraction
│   ├── Module1.Transformer_fusion.ipynb # Transformer-based feature fusion
│   ├── config.yaml              # Configuration file
│── 📂 models                # Pre-trained models
│── 📂 data                  # Dataset storage (to be provided by the user)
│── 📂 LICENSE               # License file
│── Install_Dependencies.bat # Dependency installation script
│── README.md                # Project documentation

🛠️ Installation & Execution
Environment Dependencies
Ensure that all required Python dependencies are installed. The dependency list is available in the code directory.
We recommend using Python 3.8+ and ensuring CUDA support for GPU-based training.

📝 Pre-trained Models
Some pre-trained models have been uploaded to the models/ directory.

📊 Research Background
This project leverages the CrossFormer architecture to build deep learning models for medical imaging and employs an attention mechanism-based Transformer module for feature fusion. This approach captures spatial interactions between different imaging sequences (T2WI, DWI), thereby enhancing the effectiveness of multi-parameter imaging fusion and improving the accuracy of medical image analysis.

📄 License
This project is released under the MIT License. For details, please refer to the LICENSE file.

📩 Contact
For any inquiries or collaboration opportunities, please feel free to get in touch.
