# Analysis of Filtered Outputs
Description:
This repository contains code and documentation for performing a comprehensive analysis of filtered outputs obtained from an input signal. The analysis aims to infer the type of filtering (Low Pass, High Pass, or Band Pass) applied to the input signal based on correlation analysis and visual inspection of the filtered outputs.

Files:

filter_analysis.py: Python script for implementing filters, performing convolution, computing correlation, and visualizing results.
INPUT-SIGNAL-X(t).txt: Text file containing the input signal x(t).
OUTPUT-SIGNAL-Y(t).txt: Text file containing the observed output signal 
y(t).
filter_outputs.png: Plot of filtered outputs (Low Pass, High Pass, Band Pass).
correlation_analysis.png: Plot of correlation values between filtered outputs and observed output signal.
best_matching_filter.png: Plot indicating the best matching filter type based on correlation analysis.
Usage:

Ensure Python and necessary libraries (NumPy, SciPy, and Matplotlib) are installed.
Place the input signal file (INPUT-SIGNAL-X(t).txt) and output signal file (OUTPUT-SIGNAL-Y(t).txt) in the same directory as the Python script.
Run the filter_analysis.py script to perform the analysis.
The script will generate plots of filtered outputs, correlation analysis, and best matching filter type.
Review the generated plots and analysis results to gain insights into the filtering process and determine the best matching filter type.
Dependencies:

Python 
NumPy
SciPy
Matplotlib
