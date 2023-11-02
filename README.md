# [Github Blog - zmfl.github.io](https://zmfl.github.io/)

<br>

# [목차]
### 1. [프로젝트명](#1)
### 2. [컨셉](#2)
### 3. [관련 이미지 & 동영상](#3)
### 4. [대표 이미지](#4)
### 5. [컨셉 & 대표이미지 기반 작품묘사](#5)
### 6. [< 나호 - 팬 게임 - > 구성 요소](#6)
### 7. [게임시스템디자인](#7)
### 8. [개발 요구사항 & 흐름도](#8)
### 9. [스토리보드](#9)

<br>

# 1. 프로젝트명 <a name='1'></a>
### ㆍ나와 호랑이님 - 팬 게임 - (개발자 : 염경진)

<br>

# 2. 컨셉 <a name='2'></a>
## 2-1. 메인컨셉 : 이야기
`ㆍ다른 장르와 다르게 뇌지컬 및 피지컬이 필요하지 않으며 간단하게 인물들의 이야기를 즐길 수 있다.`

## 2-2. 서브 컨셉
### 1) 선택 
`ㆍ이야기가 진행 됨에 따라 선택지가 나타나 플레이어가 이야기의 흐름을 정할 수 있다.`

### 2) 결말
`ㆍ플레이어가 선택한 이야기의 흐름에 따라 후에 이야기의 결말이 바뀐다.`

### 3) 일러스트
`ㆍ어느 인물이 어떠한 감정으로 현재 진행 중인 이야기를 말하고 느끼고 있는지 플레이어가 쉽게 알고 느끼게하여 더욱 몰입할 수 있게 한다.`

### 4) 소리
`ㆍ현재 진행 중인 이야기의 흐름에 따라 플레이어에게 여러 소리를 들려줌으로서 이야기에 몰입할 수 있게 도와준다.`

### 5) 책갈피
`ㆍ단순하고 간단하게 즐길 수 있는 게임인 만큼 자신이 현재 진행한 부분을 세이브하여 언제든지 다시 플레이할 수 있도록한다.`  
`ㆍ플레이어의 선택에 의해 이야기의 흐름 및 결말이 바뀌기도 하기에 해당 부분에서 세이브를 하여 다른 선택을 해볼 수 있도록 도와주기도 한다.`

<br><br>

# 3. [관련 이미지 & 동영상] <a name='3'></a>
<div align=center>
  
|이미지|
|:----:|
|<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/eb08b160-8b30-4aa9-aaa8-160eb6fafaaf" width="700" height="400"/>|
|동영상|
|[![Video Label](https://img.youtube.com/vi/GHcdHO9mz-4/0.jpg)](https://youtu.be/GHcdHO9mz-4)|

</div>

<br><br>

# 4. [대표 이미지] <a name='4'></a>
<div align=center>
<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/d0acb966-5037-478a-a304-80eb03195ba0" width="700" height="400"/>
</div>

<br><br>

# 5. [컨셉 & 대표이미지 기반 작품묘사] <a name='5'></a>

> ### 텍스트로 스토리가 진행된다.
> ### 현재 진행 중인 스토리에서 누구와 어떤 장소에서 대화를 하며 있는지 배경, 캐릭터 CG를 통해 보여준다.  
> ### 진행 도중 플레이어가 어떤 선택을 하는지에 따라 스토리가 달라 질 수 있는 선택지가 나온다. 

<br><br>

# 6. [< 나호 - 팬 게임 - > 구성 요소] <a name='6'></a>
> '나호'는 이 게임 스토리의 원작인 '나와 호랑이님'을 줄인 것입니다.  
>  해당 작품을 좋아하는 팬으로서 그리고 해당 작품을 기반으로 만들었기에 뒤에 -팬 게임-을 붙였습니다.

<br>

## 6-1. 메커니즘

### ㆍ[도전 과제]

`1) 여러 선택지들 중 배드엔딩으로 가는 선택지를 피해 이야기를 해피엔딩으로 이끈다.`

### ㆍ[재미 요소]

`1) 기존 원작과 달리 선택지를 이용하여 배드엔딩으로 향하는 이야기를 추가한다.`

<br>

## 6-2. 이야기
### ㆍ[만들게 된 배경]

`원작 소설을 읽을 당시 만약 어떤 특정한 부분에서 주인공이 그 행동을 안했더라면 또는 했더라면 어땟을까 라는 생각과`  
`평소 즐겨하던 비주얼노벨 게임들의 특징을 합친다면 괜찮을 것 같다는 생각으로 만들게 되었습니다.`

### ㆍ[카메라 관점]

`기본적으로 이야기 속 주인공의 1인칭 시점으로 진행됩니다.`

## 6-3. 미적요소

### ㆍ[디자인][컬러]

`학교, 산, 집안 등 여러 배경을 상황에 맞게 배치`  
`중앙 하단에 텍스트ui 배치 및 우측 하단 시스템 ui 배치`

### ㆍ[음향]
-미정

<br>

## 4. 기술

`코드 내에 텍스트를 넣어 출력하는게 아닌 외부의 텍스트 파일을 불러와 코드 내에서 처리, 출력하게 하여 텍스트를 수정 할 시 번거롭게 코드를`  
`건드리지 않아도 됩니다.`

# 7. 게임시스템디자인 <a name='7'></a>
## 7-1. 게임 오브젝트 분해
|연번|오브젝트 이름|오브젝트 이미지|
|:----:|:----:|:----:|
|1|랑이|<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/d0505d56-a6ee-4a1b-8bb8-bdc1dfaed6c8" width="150" height="150"/>|
|2|나래|<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/58cf6b10-ad0a-41d1-989c-4e6655474a8d" width="150" height="150"/>|
|3|세희|<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/974ddc14-7e08-4359-8de4-fbdb4894c638" width="150" height="150"/>|
|4|바둑이|미정|
|5|집안|<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/7cfb97be-e777-4fe2-bd77-170113bcad47" width="150" height="150"/>|
|6|학교|<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/84851ffe-c3ad-49fa-9247-cb8532f045e7" width="150" height="150"/>|
|7|산|<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/c0571588-e9eb-497c-82a9-43c8c943979b" width="150" height="150"/>|
|8|동굴|<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/9d831c33-728a-4c21-8faf-72c4c74e41a7" width="150" height="150"/>|
|9|텍스트|미정|
|10|시스템|<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/a521df19-5091-445f-813b-70e6de721f84" width="150" height="150"/>|
|11|선택지|<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/97de5072-0aa9-4e5a-ab52-1a8d5869db2f" width="150" height="150"/>|

## 7-2. 파라미터(속성)
1) 오브젝트 : 랑이, 나래, 세희, 바둑이

|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|좌표|pos|해당 오브젝트들의 상황에 따른 위치||
|상태|condition|상황에 따른 오브젝트들의 표정||

2) 오브젝트 : 집안, 산, 동굴, 학교

|속성|영문명칭|설명|비고|
|:----:|:----:|:----:|:----:|
|배경1|Home|주인공(플레이어)의 집||
|배경2|Mountain|주인공의 조부의 집이 있는 산||
|배경3|Cave|여주인공이 봉인되어있는 동굴, 어둡지만 신비로운 분위기||
|배경4|School|주인공이 다니고 있는 학교||

## 7-3. 행동
1) 오브젝트 : 랑이, 나래, 세희, 바둑이
 
|행동|영문명칭|설명|
|:----:|:----:|:----:|
|표정1|Base|기본 표정|
|표정2|Smile|상황에 따른 행복, 즐거운 표정|
|표정3|Angry|상황에 따른 화난 표정|
|표정4|Sad|상황에 따른 슬픈 표정|
|표정5|Panic|상황에 따른 당혹스러운 표정|

## 7-4. 상태
|현상태|전이상태|전이조건|
|:----:|:----:|:----:|
|표정1|표정2|스토리 진행 상황에 따른 변화|
|표정1|표정3|스토리 진행 상황에 따른 변화|
|표정1|표정4|스토리 진행 상황에 따른 변화|
|표정1|표정5|스토리 진행 상황에 따른 변화|

## 7-5. 플레이어 캐릭터 속성(파라미터)
> 해당사항 없음

## 7-6. 게임의 규칙
> 1) 핵심 규칙
>> 마우스 클릭으로 스토리를 진행시켜 진행 도중 나오는 선택지를 골라가며 엔딩을 보면 게임이 끝난다.
>> 게임이 끝난 후 재시작 함으로서 기존에 선택하지 않았던 선택지를 선택해 볼 수 있다.
>> 세이브 기능을 이용하여 처음부터 재시작하지 않아도 빠르게 다른 루트를 확인할 수 있다. 

## 7-7. 게임에서 사용될 공식
> 1) 플레이어가 어떤 선택을 했는지 저장
> 2) 플레이어의 선택에 따라 중간 스토리 변경
> 3) 플레이어의 선택 루트에 따라 최종 엔딩 변경

# 8. 개발 요구사항 & 흐름도 <a name='8'></a>

## 8-1. 요구사항
1. 스토리 정리 및 데이터 출력, 캐릭터 이미지
   1-1. 원작 1권의 절반까지 스토리 정리 및 게임화면 텍스트창에 출력  
   1-2. 랑이, 나래, 세희, 바둑이 이미지 그리기
   
3. 화면(Scene) 구성  
   2-1. 시작화면, 게임화면 총 2개의 화면이 있다.  
   
4. 시작화면 구성  
   3-1. 시작화면에는 시작과 옵션, 게임종료 버튼이 각각 있다.  
   3-2. 게임종료 버튼을 누르면 게임이 종료된다.  
   3-3. 옵션 버튼을 누르면 옵션 UI창이 나타난다.  
   3-4. 옵션 창에서는 사운드를 조절할 수 있다.  
   3-5. 옵션 창의 우측 하단에 시작화면으로 돌아갈 수 있는 버튼(Title)이 있다.  
   3-6. 시작화면에서 시작 버튼을 누르면 게임화면으로 이동한다.  
   
5. 게임화면 구성  
   4-1. 게임화면에는 하단에 텍스트창과 우측 하단에 시스템 버튼들이 존재한다.  
   4-2. 화면 전체 크기의 이미지 오브젝트가 있다. 이는 배경이미지가 들어간다.  
   4-3. 화면의 중앙 좌측부터 일정한 간격으로 이미지 오브젝트가 5개 있다. 이는 캐릭터 이미지가 들어간다.  
  
6. 플레이어 조작 구성  
   5-1. 마우스 좌클릭으로 텍스트를 넘기며 진행이 가능하다.  
   5-2. 마우스 휠을 위로 올려 이전 텍스트를 볼 수 있는 UI를 띄울 수 있다.  
   5-3. 마우스 우클릭으로 옵션화면을 띄울 수 있다.  
   5-4. 왼쪽 ctrl 키로 텍스트를 스킵할 수 있다.  
   
7. 시스템 버튼 구성  
   6-1. 세이브를 할 수 있는 세이브 버튼이 있다.  
   6-2. 세이브한 파일을 불러올 수 있는 로드 버튼이 있다.  
   6-3. 시작화면과 동일한 옵션화면을 띄울 수 있는 옵션 버튼이 있다.  
   6-4. 텍스트를 스킵할 수 있는 스킵 버튼이 있다.  
   6-5. 텍스트를 일정시간(텍스트 길이에 따라 다름)이 지나면 자동으로 넘겨주는 오토 버튼이 있다.  
   
## 8-2. 시간별 흐름도 flowchart
<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/1ae4841c-3e1e-410c-b02c-0b997ffaebce">

## 8-3. 키보드 이벤트에 대한 흐름도
<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/9f4a195c-aff0-41ba-b16a-fefbfb6931a3">

## 8-4. 용어정리
<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/21ea6355-1a22-453f-818b-0be20673603e">

# 9. 스토리보드 <a name='9'></a>
<img src="https://github.com/zmfl/zmfl.github.io/assets/23565281/1605152f-7f0a-4f4d-bab3-4386ec9b220e">
