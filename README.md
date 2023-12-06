# FCN + Detection-based-MoTe2-defect controlled -analysis


This code was created to classify defect controlled MoTe2 point defects. A total of 8 classification classes can be created.

This codew was tested for stability in Python 3.9.0 version. Therefore, we recommend using version 3.9.0.

Git clone or download this repository.

utilize requirements.txt to install the required libraries.

    pip install -r requirements.txt

Unzip fasterRCNN.egg and place the .pt file in the default directory.

Then, place the STEM images to be analyzed in the Dataset folder.

finally, go to the current directory in the anaconda prompt window and enter the code below:

    python dist/All_process.py


Results are saved in the Results folder.
