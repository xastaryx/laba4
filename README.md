
# Отчет по Лабораторной работе 4.

Я запустила в контейнере приложение “aafire” с помощью команды `docker run -it aafire` 

![Снимок экрана 2024-11-24 151220](https://github.com/user-attachments/assets/a2049b1d-8375-4c93-9568-2463ec11ecf5)
Далее я запустила два контейнера с aafire и оставила их в работающем состоянии.  
Открыла ещё одно окно терминала и создала сеть при помощи команды `docker network create myNetwork`
![Снимок экрана 2024-11-24 152813](https://github.com/user-attachments/assets/fe6831a6-d34e-4fd2-8431-ad8b493abb65)
С помощью команды `docker ps` я увидела названия контейнеров
 
 ![Снимок экрана 2024-11-24 153719](https://github.com/user-attachments/assets/465358dc-e365-43e8-bf37-8623307d3611)
После этого подключила контейнеры к своей сети с помощью команд `docker network connect myNetwork ....` и  `docker network connect myNetwork .....`

Далее я протестировала соединение между контейнерами утилитой ping

![Снимок экрана 2024-11-24 153634](https://github.com/user-attachments/assets/548d2936-b132-459e-a707-62474fba949f)



