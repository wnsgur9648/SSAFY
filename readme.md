# 181217 - Day1 (Typora, 챗봇(Python), git설치, github)



# 1. Typora 사용 방법

- #~~~~(h1)





## h2 사용

- ##~~~~(h2)





### h3 사용

- ###~~~~(h3)





#### h4 사용

- ####~~~~(h4)





●(점) 찍는 방법

- -를 입력하고 Space bar를 입력한다.

 



숫자로 들여쓰기

- 숫자를 쓰고 .을 찍고 space bar를 누른다.

ex) 

1. 
2. 





코드 입력하는 방법

- `로 코드 내용을 감싸주면 된다.

ex)

123`Code`가나다라





한줄 전체를 코드 블럭으로 만드는 방법

- `을 3개 입력하고 원하는 언어를 적어준다.
- 원하는 언어를 적어주면 해당 언어의 문법에 맞게 인식을 한다.

ex)

```python
def cal():
    return a+b
```





코드 입력시 유의사항

- 코드를 입력하고 그 위에 해당 코드가 들어가야 하는 파일 이름을 italic체로 적어주거나 코드 블럭안에 주석으로 넣어준다.
- italic체를 적는 방법 -> * 으로 바꾸고자하는 곳을 감싸준다. -> * example *

ex)

*app.py*

```python
#app.py
def cal():
    return a+b
```





bold 표현

- bold 처리를 하기 위해서는 * 두개로 감싼다.
- #####도 bold와 같은 크기이다.

ex) ** 가나다라 ** -> **가나다라**





링크(link) 거는 방법

- [] -> 링크를 걸고자하는 문구에 대괄호로 감싼다.
- () -> 링크가 걸린 문구를 눌렀을 경우 소괄호안에 있는 URL로 이동

ex) [] () ->대괄호와 소괄호 사이 space가 없어야한

​	[이것은 링크입니다.] (https://www.naver.com)





이미지 넣는 방법

- ![] () -> ()안에 이미지의 URL 주소를 넣어주면 된다. -> []와 ()사이에 space가 들어가면 안된다.

ex) ![] (~~~~)

![](data:image/jpeg;base64,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)



예외사항 표시하는 방법

- 예외사항을 넣을 문구 앞에 >를 입력한다.

ex)

> 예외사항





표 만드는 방법

- 본문 -> 표를 선택해서 원하는 크기(행, 렬)를 입력한다.

ex)

| 원하는 | 표를 | 만들어보자. |
| :----: | :--: | :---------: |
|        |      |             |
|        |      |             |
|        |      |             |





# 2. 챗봇(Python)



카카오톡 챗봇 친구추가

1. @sspy-003 검색

2. 친구 추가

   > 다른 반과 섞이지 않도록 주의

3. 안녕 메세지 보내서 인증번호 받기

4. 인증번호 받아서 채팅창에 입력하기

5. 인증 완료





봇 메시지



점심메뉴

```python
import random
menu = ["순남 시레기","멀티캠퍼스 20층","양자강","강남 목장", "시골집"]
menu_detail={"순남 시레기" : "시레기국, 보쌈","멀티캠퍼스 20층" : "오늘의 메뉴","양자강" : "차돌 짬뽕","강남 목장" : "뚝배기 불고기", "시골집" : "쌈밥 정식"}

lunch = random.choice(menu)
print(lunch+"에서는 "+menu_detail[lunch]+"이(가) 먹을만 합니다.")
```



미세먼지

```python
import requests
from bs4 import BeautifulSoup

url = 'http://openapi.airkorea.or.kr/openapi/services/rest/ArpltnInforInqireSvc/getCtprvnRltmMesureDnsty?sidoName=%EC%84%9C%EC%9A%B8&ServiceKey={}&ver=1.3&pageNo=3'.format(key)
response = requests.get(url).text
soup = BeautifulSoup(response, 'xml')
gn = soup('item')[7]
location = gn.stationName.text
time = gn.dataTime.text
dust = int(gn.pm10Value.text)

print('{0} 기준: 서울시 {1}의 미세먼지 농도는 {2} 입니다.'.format(time, location, dust))

#조건문
if dust<=30:
  print("오늘의 미세먼지 농도는 좋음 입니다.")
elif 31<=dust<=80:
  print("오늘의 미세먼지 농도는 보통 입니다.")
elif 81<=dust<=150:
  print("오늘의 미세먼지 농도는 나쁨 입니다.")
elif dust>=151:
  print("오늘의 미세먼지 농도는 매우 나쁨 입니다.")
```



반복문 예제

```python
dish = ["삼겹살", "꽃등심", "파스타", "뚝배기 불고기", "폭찹"]

# 1. for문을 이용해서 dish에 담겨있는 모든 음식을 먹는 코드를 작성
for i in dish:
  print("{}을/를 먹었습니다.".format(i)) 
print("")

# 2. while문을 이용해서 dish에 담겨있는 모든 음식을 두번씩 먹는 코드를 작성
for i in dish:
  j=0
  while j<2:
    print("{}을/를 먹었습니다.".format(i)) 
    j+=1
```



날씨

```python
import requests

url = "https://api.openweathermap.org/data/2.5/weather?q=Seoul,kr&lang=kr&APPID="+key
data = requests.get(url).json()
#requests => 기능 뭉탱이
#.get => requests가 가진 기능 중 하나를 사용해서 또 하나의 기능 뭉탱이를 밷어낸다.
#.json => 위에서 나온 기능 뭉탱이의 기능 중 하나
# => 이런 식으로 계속 붙여가는게 메소드 체이닝

weather = data['weather'][0]['description']
temp = float(data['main']['temp'])-273.15
temp_min = float(data['main']['temp_min'])-273.15
temp_max = float(data['main']['temp_max'])-273.15
wind = data['wind']['speed']
visibility =data['visibility']

print("""서울의 오늘 날씨는 [{}] 이며, 섭씨 {:.1f}도 입니다.
최저/최고 온도는 {:.1f}/{:.1f}도 입니다.
현재 풍속은 {:.1f}m/s이며 가시거리는 {}m입니다.
""".format(weather, temp, temp_min, temp_max, wind, visibility)
)
```



JSON 형식

```json
{
    'coord': {'lon': 126.98, 'lat': 37.57}, 
    'weather': [{'id': 721, 'main': 'Haze', 'description': '연무', 'icon': '50d'}], 
    'base': 'stations', 
    'main': {'temp': 279.11, 'pressure': 1018, 'humidity': 30, 'temp_min': 278.15, 'temp_max': 279.95}, 
    'visibility': 10000, 
    'wind': {'speed': 3.1, 'deg': 280}, 
    'clouds': {'all': 0}, 
    'dt': 1545026400, 
    'sys': {'type': 1, 'id': 8105, 'message': 0.0065, 'country': 'KR', 'sunrise': 1545000046, 'sunset': 1545034526}, 
    'id': 1835848, 
    'name': 'Seoul', 
    'cod': 200
}

```





# 3. git 설치



１. git for windows를 검색한 후 설치를 진행한다.(설정은 default로 설치)

２. github 가입 후 인증

３. repository를 원하는 이름은 생성

４. git bash를 실행 후 아래의 명령어를 따라서 친다. 이때  pwd를 치고 자신이 있는 경로에 github로 업로드 하고자 하는 파일이 있는지를 확인한다.

**$ git init**

**$ git add .**

**$ git commit -m "first commit"** (당연히 안됨-> 설정이 다 안되어 있음)

*** Please tell me who you are.

Run

  **git config --global user.email "you@example.com"**

  **git config --global user.name "Your Name"**		두개의 명령어를 자신의 인증 이메일과 닉네임으로 설정

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'student@M70213.(none)')

**$ git config --global user.email "wnsgur9648@naver.com"

**$ git config --global user.name "wnsgur9648"**

**$ git commit -m "first commit"**
[master (root-commit) 0255a8d] first commit
 1 file changed, 81 insertions(+)
 create mode 100644 readme.md

**$ git remote add origin https://github.com/wnsgur9648/SSAFY.git

**$ git push -u origin master**





문서 수정후 재 업로드

**$ git status**

**$ git diff**

**$ git add .**

**$ git commit -m "second commit"**

**$ git push**



