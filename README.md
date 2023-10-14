# 프로젝트명 : Undocked(1988037 이휘재)

# [컨셉]

## 메인컨셉 : 탈출

- 행성을 탐사하기 위해 만든 기지에서 의문의 사고로부터 탈출하는 컨셉을 통해 SF적인 요소를 더함으로써 유저들에게 흥미를 준다.
- 탈출이라는 목표를 설정함으로써 게임 클리어 후에 해방감을 느낄 수 있도록 한다.

### 서브 컨셉 1 : 전투

- fps 요소를 활용하여 원거리 공격으로 적과 전투를 한다.
- 공격 시 다양한 이펙트를 통해 타격감을 준다. 

### 서브 컨셉 2 : 길 찾기

- 플레이어는 맵 어딘가에 있는 목표지점을 찾아 이동해야한다.

### 서브 컨셉 3 : 생존

- 적의 공격으로부터 생존해야 한다.
- 플레이어에게 체력을 부여하고 체력을 관리하도록 해 게임이 지루하지 않게 한다. 

### 서브 컨셉 4 : 적 AI

- 적에게 ai를 부여해 플레이어에게 접근하거나 공격하도록하여 플레이어에게 긴장감을 준다.

### 서브 컨셉 5 : 지형 상호작용

- 아이템을 활용해 통행에 방해되는 지형을 부숴 길을 터 이동할 수 있다.
- 퍼즐 요소로 게임 클리어 조건으로 작용된다.

<br><br>

# [관련 이미지 & 동영상]

- 이미지  
  <img src="./img/관련이미지 1.jpg"><br>
- 동영상
  [![](./img/동영상이미지.jpg)](https://youtu.be/MC2R2yogiAo?t=79)

<br><br>

# [대표 이미지]

![그림](./img/대표이미지.png)<br>

<br><br>

# [컨셉 & 대표이미지 기반 작품묘사]

> ### 대표이미지 기반 :

> ### 컨셉 기반:

<br><br>

# [<Undocked> 구성 요소]

- 행성 탐사 기지에서 탈출하는 생존 FPS게임

<br>

## 1. 메커니즘

[도전 과제]

1. 플레이어에게 접근하고 공격하는 적들을 제거하여 생존.
2. 탈출 지점까지 길을 찾아 도착한다.
3. 탈출에 필요한 아이템을 획득하여 탈출에 성공한다.

[재미 요소]

1. 일정 반경 접근 시 공격하는 적, 빛을 감지하는 적 AI
2. 탈출 지점까지 길을 직접 찾아야 한다.
3. 아이템을 사용하여 장애물 파괴
4. 문을 열 수 있는 아이템이나 단서를 모으는 퍼즐 요소

<br>

## 2. 이야기

[만들게 된 배경]  
- 외계 행성 탐사 기지에서 외계 생명체들로부터 생존하는 sf 요소를 fps 게임에 
적용함으로써 플레이어들에 긴장감을 더할 것이라고 생각했다.
- 먼 우주에서 혼자 남은 막막한 상황에서 끝까지 살아남아 
탈출했을 때(게임을 클리어했을 때) 성취감과 해방감을 느낄 것이라고 생각했다.

[카메라 관점]  
- 1인칭 시점으로 총을 들고 있는 플레이어의 손이 보인다.
- 플레이어가 적으로부터 피격 시 카메라 흔들림 효과가 구현된다.

<br>

## 3. 미적요소

[디자인]
- 행성 탐사 기지라는 배경 컨셉에 맞는 SF 느낌의 모델로 맵을 제작한다.
- 기괴한 외계 생명체 모델을 적 오브젝트로 사용한다.

[컬러] 
- 라이트를 조절하여 전체적으로 어두운 분위기를 만들어 게임에 긴장감을 더한다.

[음향]  
- 긴장감을 주기 위해 조용하고 공허한 배경음악으로 플레이어의 발소리를 부각시킨다.
- 적대적인 외계 생명체를 표현하기 위해 적에게 기괴한 사운드를 적용한다.<br>

<br>

## 4. 기술
- 유니티 3D를 이용하여 구현할 예정이다.

# [게임 시스템 디자인]
### 게임 오브젝트 분해
|연번|오브젝트 이름|오브젝트 이미지|
|:----:|:----:|:----:|
|1|플레이어|<img src="./img/player.png" width="300">|
|2|총|<img src="./img/gun.png" width="300">|
|3|집게 외계 종족 일반|<img src="./img/alien_crab.png" width="300">|
|4|집게 외계 종족 강화|<img src="./img/crab_mutant.png" width="300">|
|5|외계 돌연변이|<img src="./img/alien_mutant.png" width="300">|
|6|인간 숙주 돌연변이|<img src="./img/slider_mutant.png" width="300">|
|7|렙틸리언|<img src="./img/reptile.png" width="300">|
|8|타이탄알파|<img src="./img/titan_alpha.png" width="300">|
|9|총알|<img src="./img/bullet.png" width="300">|
|10|소형 폭탄|<img src="./img/wall_bomb.png" width="300">|
|11|힐팩|<img src="./img/heal_pack.png" width="300">|
|12|배터리|<img src="./img/battery.png" width="300">|
|13|모듈식 벽|<img src="./img/wall.png" width="300">|
|14|모듈식 천장 패널|<img src="./img/ceiling panel.png" width="300">|
|15|모듈식 통로|<img src="./img/walkway.png" width="300">|
|16|선반|<img src="./img/shelf.png" width="300">|
|17|sf 상자|<img src="./img/sf_box.png" width="300">|
|18|sf 팔레트|<img src="./img/sf_pallet.png" width="300">|
|19|소화기|<img src="./img/fire_exting.png" width="300">|
|20|벽 파이프|<img src="./img/pipe_wall.png" width="300">|
|21|sf 문|<img src="./img/sf_door.png" width="300">|
|22|우주선|<img src="./img/spaceship.png" width="300">|
|23|탄약 상자|<img src="./img/ammo_box.png" width="300">|
|24|부서지는 벽|<img src="./img/breaking_wall.png" width="300">|
|25|잠겨있는 문|<img src="./img/door_locked.png" width="300">|
|26|비밀번호 숫자 패드|<img src="./img/keypad.png" width="300">|
|27|랩탑|<img src="./img/laptop.png" width="300">|
|28|배터리 디스플레이|<img src="./img/tablet_pc.png" width="300">|
|29|플레이어 체력 UI|<img src="./img/.png" width="300">|
|30|전체 총알 개수 UI|<img src="./img/축구장.png" width="300">|
|31|탄창 총알 개수 UI|<img src="./img/축구장.png" width="300">|
|32|비밀번호 UI|<img src="./img/password_ui.png" width="300">|
|33|우주선 배터리 잔여략 UI|<img src="./img/battery_check_ui.png" width="300">|




































