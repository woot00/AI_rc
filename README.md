# AI_rc
2장, Jetpack & ROS install

https://drive.google.com/file/d/1HU5F1cwiw2wzuNBdLL9R3Wvpg5AXLzw5/view?usp=sharing

id: jetson
passwd: jetson

1.2 Cooling Fan

cd Downloads
git clone https://github.com/jetsonworld/jetson-fan-ctl.git
cd jetson-fan-ctl

  jtop 사용

   I2C 장치 연결 확인

   OLED를 연결한 경우 3c가 보일 것입니다.  PCA9685까지 연결하면 40, 70이 나타나야합니다. 단 address를 변경한 PCA9685인 경우 변경된 address가 보일 것입니다.  또는 보드 종류에 따라 41, 60등 추가 번호가 나오기도합니다.(예: Waveshare Jetracer)  Driver, 추가 구성에 따라 결과는 달라집니다.

   2.1 ROS Melodic 설치

jugfk에 있는 script가 pgp key 때문에 동작하지 않아 shell을 수정했습니다. zeta0707 github에서 clone합니다.

sudo sh install.sh
sudo sh install.sh 명령어는 리눅스나 macOS와 같은 유닉스 기반 운영 체제에서 사용하는 명령어입니다. 이 명령어는 다음과 같이 작동합니다:

sudo: "superuser do"의 약어로, 명령어를 관리자 권한으로 실행하도록 하는 명령어입니다. 즉, 시스템 관리자 권한이 필요한 작업을 실행할 때 사용합니다. 관리자 권한은 시스템 설정 변경과 같은 중요한 작업에 필요합니다.

sh: 셸 스크립트를 실행하는 명령어입니다. 셸 스크립트는 명령어와 명령어의 연속이 스크립트 파일에 저장된 것이며, 스크립트 파일을 실행하여 여러 작업을 자동화할 수 있습니다. sh은 기본적으로 셸 스크립트를 실행하는 데 사용되는 셸 인터프리터입니다.

install.sh: 이 명령어는 install.sh라는 스크립트 파일을 실행하라는 것을 의미합니다. install.sh 파일은 어떤 종류의 설치 프로세스나 스크립트를 나타낼 수 있으며, 이 스크립트를 실행하면 파일의 내용대로 작업이 수행됩니다.

따라서 sudo sh install.sh 명령어는 install.sh라는 스크립트 파일을 관리자 권한으로 실행하는 것을 의미합니다. install.sh 파일의 내용과 스크립트가 무엇을 수행하는지는 파일의 내용에 따라 다를 것이며, 이 스크립트가 어떤 소프트웨어나 작업을 설치 또는 수행하는 것에 따라 역할이 달라집니다.
