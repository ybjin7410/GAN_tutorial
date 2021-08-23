# GAN_tutorial with PyTorch
### MNIST & CIFAR10 데이터 셋을 이용한 GAN/DCGAN의 구현
### paper
[[Generative Adversarial Nets]](https://arxiv.org/pdf/1406.2661.pdf)  
***************
## Description

* model: 학습된 Generator, Discriminator가 저장됨.  
* result: 각 데이터 셋/ 모델 구조에 따른 이미지 생성 결과가 저장됨.  
* ipynb 파일:   
	- [x] GAN_pseudo.ipynb: GAN 학습의 이해를 돕기 위한 pseudo code
	- [x] MNIST_GAN.ipynb: MNIST를 이용한 GAN 학습
	- [x] MNIST_DCGAN.ipynb: MNIST를 이용한 DCGAN 학습
	- [x] CIFAR10_DCGAN.ipynb: CIFAR10을 이용한 DCGAN 학습
***************
## Model architecture
* GAN
![GAN_architecture](https://user-images.githubusercontent.com/52904626/130410234-fed5d825-59f9-400d-ae0b-bc656eeea630.png)

***************
## Resutls
### MNIST
<table align='center'>
<tr align='center'>
<td> GAN</td>
<td> DCGAN</td>
</tr>
<tr>
<td><img src = 'mnist_gan.gif'>
<td><img src = 'mnist_dcgan.gif'>
</tr>
</table>
### MNIST
<table align='center'>
<tr align='center'>
<td> DCGAN</td>
</tr>
<tr>
<td><img src = 'cifar_dcgan.gif'>
</tr>
</table>
