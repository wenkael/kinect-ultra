# Working Configurations #

@en This is the list of the hardware/software configurations where this program is reported to work (or not to work). **Please use comment to let me know of your configurations.**

@ja 動作報告(または動作しなかった報告)のあった構成です。**あなたの構成をコメントで教えてください。**

## Work ##

### Platform ###

| **CPU**        | **GPU**           | **OS**                | **Reported by** | **Remark** |
|:---------------|:------------------|:----------------------|:----------------|:-----------|
| Core i7 2600   | GeForce GTX 285   | Win 7 Pro 64          | tomoto          |            |
| Core i7 920    | GeForce GTX 285   | Win XP Pro 32         | tomoto          |            |
| Core i7 950    | GeForce GTX 460   | Win 7 Home 64         | sei0178         |            |
| Core i7 920    | Radeon 4890       | Win 7 Home Prem 64    | mike.lightfox   |            |
| Xeon 3470      | Quadro FX 3800    | Win XP 64             | Jiang           |            |
| Core 2 Quad    | GeForce 8800      | Win Vista Home Prem 32 | Ismael          |            |
| Core 2 Duo U9300  | Mobile Intel 4 Series Express (`*1`) | Win XP Pro 32         | tomoto          | Very low frame rate |
| Amdx2 64 3200  | GeForce 9500GT    | Win 7 Pro             | rg7strin...     |            |
| Core 2 Athlon II X2 250@3GHz | Radeon HD 5700    | Win 7 Pro 64          | dim...          |            |
| Core i3-350M@2.26GHz | GeForce 310M (512MB) |                       | coji...         |
| Celeron U3400@1.07GHz | Intel             |                       | sergey.s...     | Slowly     |
| Core i5@3GHz   | Intel HD Graphics | Win 7                 | koyanagister    |            |


(`*1`) Driver version = 6.14.10.5303. Note 6.14.10.4953 does not support shader.

### Kinect SDK ###

| **Kinect SDK** | **Remark** | **Reported by** |
|:---------------|:-----------|:----------------|
| 1.5            |            | tomoto          |
| 1.0            |            | tomoto          |

### OpenNI & Kinect Drivers ###

| **OpenNI** | **NITE** | **Kinect Driver** | **Remark** | **Reported by** |
|:-----------|:---------|:------------------|:-----------|:----------------|
| 1.5.2.23   | 1.5.2.21 | kinect-mssdk-openni-bridge 1.5.0.0 for 1.5.2.23 + Kinect SDK V1.5|            | tomoto          |
| 1.5.2.23   | 1.5.2.21 | SensorKinect by avin2 5.0.3.4 |            | tomoto          |
| 1.3.4.3    | 1.4.2.4  | SensorKinect by avin2 5.0.3.4 | ZigFu's all-in-one package | tomoto          |
| stable 1.3.3.6 | stable 1.4.2.4 | SensorKinect by avin2 5.0.3.4 |            | tomoto          |
| unstable 1.1.0.41 | unstable 1.3.1.5  | SensorKinect by avin2 5.0.1 | Obsolete   | tomoto          |
| alpha 1.0.0.23 | 1.3.0.17 | SensorKinect by avin2 5.0.0 | Obsolete   | tomoto          |
| unstable 1.0.0.25 |          | SensorKinect by avin2 5.0.0 | Obsolete   | mike.lightfox   |
| unstable 1.1.0.41 | 1.3.1.5  | SensorKinect by avin2 5.0.1 | Obsolete   | Tomoto          |

## Not Work ##

| **CPU**             | **GPU**          | **OS**               | **Reported by** | **Remark** |
|:--------------------|:-----------------|:---------------------|:----------------|:-----------|
| Celeron 550@2GHz    | Intel 82GM965    | Win XP Pro 32        | Dillony         | GPU only supports OpenGL 1.5 |