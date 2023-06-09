
# URDT
# Unlimited-Resolution Diffusion Transformer: A Patch-Cycle Diffusion Model for Progressive Image Restoration
<!By Liyan Wang, Qinyu Yang, Bo Fu, Ximing Li, and Zhixun Su> 

# Updating!!!

## Coarse Training Pipeline and DT Network

<img src = "https://github.com/wlydlut/URDT-main/blob/main/Figs/fig1.png#pic_center"> 

## Fine Training Pipeline and Sampling

<img src = "https://github.com/wlydlut/URDT-main/blob/main/Figs/fig2.png#pic_center"> 

## Requirements
- CUDA 10.1 (or later)
- Python 3.9 (or later)
- Pytorch 1.8.1 (or later)
- Torchvision 0.19
- OpenCV 4.7.0
- tensorboard, skimage, scipy, lmdb, tqdm, yaml, einops, natsort

## Training and Evaluation

Training and testing instructions and visualization results for Image Deraining, Image Motion Deblurring, and Real Image Denoising are provied in the links below. 

<table>
  <tr>
    <th align="center">Task</th>
    <th align="center">Training</th>
    <th align="center">Testing</th>
    <th align="center">URDT's Visual Results</th>
  </tr>
  <tr>
    <td align="center">Image Deraining</td>
    <td align="center"><a href="Deraining/README.md#training">Link</a></td>
    <td align="center"><a href="Deraining/README.md#testing">Link</a></td>
    <td align="center"><a href="https://drive.google.com/drive/folders/1v4aAFDAojHtedtRmPcqVKJcAixW5dZ8m">Download</a></td>
  </tr>
  <tr>
    <td align="center">Image Motion Deblurring</td>
    <td align="center"><a href="Motion_Deblurring/README.md#training">Link</a></td>
    <td align="center"><a href="Motion_Deblurring/README.md#testing">Link</a></td>
    <td align="center"><a href="https://drive.google.com/drive/folders/1qYVPblP0kCyfIoxDQ2NBsdbv_MoZ24S4">Download</a></td>
  </tr>
  <tr>
     <td align="center">Real Image Denoising</td>
    <td align="center"><a href="Denoising/README.md#training">Link</a></td>
    <td align="center"><a href="Denoising/README.md#testing">Link</a></td>
    <td align="center"><a href="https://drive.google.com/drive/folders/1hgSYcwSLktFh42LA9bDXTLUuNzThdJVA">Download</a></td>
  </tr>
</table>

## Experimental Results

<details>
<summary><strong>Image Deraining</strong> (click to expand) </summary>

<p align="center"><img src = "https://github.com/wlydlut/URDT-main/blob/main/Figs/tab1.png#pic_center"></p> 
<p align="center"><img src = "https://github.com/wlydlut/URDT-main/blob/main/Figs/fig3.png#pic_center" width="1000"></p> 

</details>

<details>
<summary><strong>Image Motion Deblurring</strong> (click to expand) </summary>

<p align="center"><img src = "https://github.com/wlydlut/URDT-main/blob/main/Figs/tab2.png#pic_center" width="500"></p>
<p align="center"><img src = "https://github.com/wlydlut/URDT-main/blob/main/Figs/fig4.png#pic_center" width="1000"></p>
</details>

<details>
<summary><strong>Real Image Denoising</strong> (click to expand) </summary>

<p align="center"><img src = "https://github.com/wlydlut/URDT-main/blob/main/Figs/tab3.png#pic_center" width="500"></p>
<p align="center"><img src = "https://github.com/wlydlut/URDT-main/blob/main/Figs/fig5.png#pic_center" width="1000"></p>
<p align="center"><img src = "https://github.com/wlydlut/URDT-main/blob/main/Figs/fig6.png#pic_center" width="1000"></p>
</details>

## Contact
<!Should you have any questions, please contact wangliyan@mail.dlut.edu.cn >


**Acknowledgment:** This code is based on the [BasicSR](https://github.com/xinntao/BasicSR) toolbox and [Restormer](https://github.com/swz30/Restormer), [WeatherDiffusion](https://github.com/IGITUGraz/WeatherDiffusion). 

