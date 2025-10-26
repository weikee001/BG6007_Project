# BG6007_Project

The following steps (using the paper's code as a reference) were employed for the implementation of hypoxemia prediction through videos recorded using an iPhone14 pro: 
Step 1 - process MP4 videos and add header to the csv output (R,G,B)
Step 2 - preprocess data to h5 file for step 3 (modifications made: to process the files for patient 100007 without groundtruth data)
Step 3 - visualization and training of the data 

For the improved version of the files (Step 1 and Step 3), modifications to the code to improve signal accuracy, extracting the region of interest (ROI) from the centre of the fingertip

Note:
- Paper: Hoffman et al. “Smartphone camera oximetry in an induced hypoxemia study”, npj Digital Medicine, 2022
- patient 100007: newly added light-skin participant with no groundtruth data obtained
- did not upload the raw-videos data due to size constraints
