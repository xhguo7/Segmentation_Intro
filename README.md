# Brain MRI Image Segmentation


# 1. Usage Instruction

## 1.1 Installation

Please note that `matplotlib` is used in this repo for visualization. Please install `matplotlib` before running the code if you are running locally. 

`pip install matplotlib`



## 1.2 Data

We are using the Kaggle public dataset: 
* [LGG Segmentation Dataset](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation) for brain MRI segmentation
* [Download dataset](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation/download?datasetVersionNumber=2)

After downloading the brain MRI dataset, please save the data following this path:

`/dataset/lgg-mri-segmentation/kaggle_3m/`



## 1.3 Run

Please download the dataset before running our code: 
* Save data to `/Brain_MRI/dataset/lgg-mri-segmentation/kaggle_3m/`
* Save our trained model `brain-mri-segmodel.h5` to `/Brain_MRI/model/`
* Save our code file `brain_MRI_segmentation.ipynb` to `/Brain_MRI/`

Now you are ready to run! 
* Use notebook to run our code `brain_MRI_segmentation.ipynb` cell by cell
* Our [code](https://github.com/xhguo7/BrainMRI_Segmentation/brain_MRI_segmentation.ipynb)

Brain MRI segmentation: 
* Use our trained model to run: our model is in the path `/model/brain-mri-segmodel.h5`
* May use our model directly for segmentation: `brain_MRI_segmentation_prediction.ipynb`



# 2. References

[1] [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/pdf/1505.04597.pdf)

[2] [UNet++: Redesigning Skip Connections to Exploit Multiscale Features in Image Segmentation](https://arxiv.org/pdf/1912.05074.pdf)

[3] [ResUNet-a: a deep learning framework for semantic segmentation of remotely sensed data](https://arxiv.org/pdf/1904.00592.pdf)

[4] [Association of genomic subtypes of lower-grade gliomas with shape features automatically extracted by a deep learning algorithm](https://arxiv.org/pdf/1906.03720.pdf)
