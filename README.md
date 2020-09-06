# SRCV
Spectrum recognition based on computer vision: A tool for 13C and 1H  NMR data extraction from already analyzed spectra

SRCV
This is the repository of codes for the paper entitled “Machine learning enhanced spectrum recognition system SRCV for intelligent NMR data extraction”. This repository contains the source codes, datasets for number recognition training and test, and 1D NMR spectra examples for NMR data extraction. 

Number recognition
Number recognition is the key procedure for NMR data extraction, and three machine learning models, i.e., AdaBoost, SVM, and kNN, were pretrained for this task. Training sets and test sets examples are included in the trainset folder and testset folder. 

Installation and Usage
The Visual Studio C++ and OpenCV 4.2.0 have to be installed and configurated on the local machine. The examples-input folder contains the example spectra for SRCV usage. The corresponding results are included in the examples-output folder. The SRCV_NMR_chart_data_format （https://github.com/zhuoyang357/SRCV_NMR_chart_data_format） can also be installed for adjusting the output format of 1H NMR data extraction results. 

Contact: yangzhuo@imm.ac.cn


