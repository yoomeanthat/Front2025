git config --global user.email "yoomeani1214@gmail.com"
  git config --global user.name "yoomeanthat"

 git add .
git commit -m "설명"
git push origin main

--원격주소 확인--
git remote -v

git config --global user.email "yoomeani1214@gmail.com"
git config --global user.name "yoomeanthat"

1.
flex-wrap: wrap;    /* 줄바꿈*/

2.
day4_정리\css문법\06_인접형제선택자.html

3.
day4_정리\css문법\08_가상클래스선택자_ active.html

4.
flex-direction: column;

5.<del></del> => 삭제 <ins></ins> => 밑줄

6.
day13(1.23)\test.html

7.
setTimeout  setInterval

8.
gap: 20px
flex-direction: column; => 아이템들을 세로로 나열한다



9.노래 가능
088DhoP0SaU     10cm                  (1시간)
CBG8waSkazE     2Ne1                  (1시간)
ishEghqlppE     2000년대 초반 발라드         (1시간)
xDv9XZc8VTQ     HYBS                  (1시간)
wo7qRZ8rQ5A     MC 더 맥스             (1시간)
-hMVsGL-4nA     김필                (1시간)
sEKFI5fC_ls     다비치               (1시간 30분)
sYwBQvZIIes     무한도전 가요제 모음  (1시간 50분)
f4jS6yW83MU     멜로망스, 폴킴, 볼빨간사춘기 등   (2시간)
2Vx3dGbCwBc     멜론차트 7월 1일    (1시간20분)
RM--kHmRZKw     성시경                (1시간)
FbWpvP-uVlo     시원한? 느낌의 10cm,로이킴 등    (2시간)
6ww68vgN1n8     슈스케 노래           (1시간)
i7fqdNW3pHo     싸이                (1시간)
L4gRnvq38Vk     발라드 모음           (12시간)
g4inYK1jsdY     발라드 노래모음             (2시간)  
LyX4DvoYWXI     발라드              (1.5시간)
S3wNhK3BZXk     발라드 아련한 느낌    (1시간)
ZwlaH_dzfMc     발라드 (3)          (2.5시간)
vyU-rMfgV80     발라드 (4)             (1시간)
WGkqjzJOXj8     발라드 (5)           (1시간)
VoBxz3sF-0E     버스커버스커         (1시간)
2xrC70Zt3lM     비오는 날 듣는 플리     (1시간 20분)
RSBbwt0b2ho     비스트 빅뱅 틴탑        (50분)
OsA3iPO2fEg     빅뱅                    (1시간 47분)
RIUq-yvToPI     백예린                  (2시간 30분)
s-JK1qxx6nM     백예린                  (2시간)
B57ZgrQtOls     여름 걸그룹 케이팝      (1시간 20분)
5YKL_1wbUnw     위너                        (1시간)
chBxJw-kYiQ     이무진                        (2.5시간)
_Lr5VTwYi1k     이무진                  (2시간)
MY8gu-1eb4s     이무진                  (2.5시간)
jixVc4jww-k     인디 (정새벽, 밤마루 등)    (2시간)
YAtMR0NBXe4     폴킴          (2시간)
aZmsTX0-KAE     혁오           (30분)
isFo2edeAkY     7월 9일 케이팝 플리   (1시간)
fLPduVgylFw     7월 12일 케이팝        (1시간)






function checkAndPlaySound() {
  if (!playerReady) return;

  const now = new Date();
  const day = now.getDay(); // 추가
  const hours = now.getHours();
  const minutes = now.getMinutes();
  const seconds = now.getSeconds();

  // 주말에만 실행
  const isWeekend = (day === 0 || day === 6); //추가

  if (!isWeekend) return; //  추가

  
