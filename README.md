# Network
Network 정리





# 네트워크란 ? 
분산되어있는 컴퓨터들이 자원을 공유할 수 있게 통신망으로 연결.



![image](https://user-images.githubusercontent.com/35188271/219922795-249cec2f-0cf4-4d99-badc-2687b646e2c9.png)
![image](https://user-images.githubusercontent.com/35188271/219922803-6c9166e8-d531-45e0-98e8-54e22074a7a6.png)



- LAN(Local Area Network) : 근거리 통신망(사무실, 학교 등 가까운 지역을 한데 묶은 네트워크)
- WAN(Wide Area Network) : 장거리 통신망
- VPN(Virtual Private Network) : 가상 사설망


![image](https://user-images.githubusercontent.com/35188271/219950005-c9e65e4c-ac5b-4f06-a0f1-191f38760471.png)
![image](https://user-images.githubusercontent.com/35188271/219950012-10e3c110-caf3-479a-8c78-665dbc7cf6b5.png)
![image](https://user-images.githubusercontent.com/35188271/219950029-a046c01b-3e79-4098-b838-74d1382b2692.png)



# OSI 7 Layer
![image](https://user-images.githubusercontent.com/35188271/219950171-884e3f5e-7cef-4ba1-aad2-d5b4165226fe.png)

- 1계층 : 디지털 Bit(0과1)을 Analog로 전환하여 케이블을 통해 전송 (케이블,인터페이스,허브=브로드캐스팅,리피터=장거리 전송시 신호를 다시 증폭하여 재전송함)
- 2계층 : 동일 네트워크내에서 MAC통신, 물리계층에서 발생할 수 있는 오류를 감지하고 수정,MAC=신뢰성 보장없이 데이터 전송, LLC=신뢰성 있는 패킷 제공.(모뎀, 스위치)  
![image](https://user-images.githubusercontent.com/35188271/219951557-9e835e1e-c7a5-4e53-98f5-126a5eb2e2fa.png)
- 3계층 : 다른 네트워크끼리 IP통신, 라우팅 처리  
- 4계층 : TCP,UDP 등 Port를 제어 / L4로드밸런싱
- 5계층 : 세션 수립,해제 IP+Port를 묶어서 세션테이블로 관리
![image](https://user-images.githubusercontent.com/35188271/219952174-93221fcf-6723-4a1a-9856-126f2597922c.png)
- 6계층 : 프로그램과 네트워크간 데이터를 변환(인코딩,디코딩,암호화,압축, ACII,JPG,MPEG등)  
- 7계층 : 사용자가 사용하는 소프트웨어 (SMTP,FTP 등)  
  
![image](https://user-images.githubusercontent.com/35188271/219952467-0da57bf4-a942-47b3-9aea-0b6e473f0d2e.png)  
- `ICMP(Internet Control Message Protocol)` : ICMP는 도착지 호스트가 없거나, 포트가 닫혀 있는 등의 에러 상황이 발생할 경우 IP헤더에 기록되어 있는 출발지 호스트로 에러에 대한 정보를 보내주는 역할을 한다

![image](https://user-images.githubusercontent.com/35188271/219952696-ee495b28-9e7e-4354-a4f8-5fe39314df84.png)


- `스위치` : MAC주소 기반 통신, 라우팅 기능이 있으면 L3스위치라고 한다.
- `ARP(Address Resolution Protocol)` : IP주소를 통해서 MAC주소를 알려주는 프로토콜.  
![image](https://user-images.githubusercontent.com/35188271/219953878-69629064-fc1f-4727-978f-f00cbd9f88fb.png)
- `DHCP(Dynamic Host Control Protocol)` : 
![image](https://user-images.githubusercontent.com/35188271/219954553-140de058-a43d-4648-abfc-d486bbd23797.png)
