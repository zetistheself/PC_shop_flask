## Адрес ##

Сайт находится по адресу http://45.156.25.91/

## Идея и предназначение ##

PcHub - проект, который поможет людям выбрать компьютер под свои задачи и бюджет.
На сайте представлены эталонные сборки под каждый бюджет

## Функционал ##

Есть возможность зарегистрироваться и входить в свой аккаунт.
В профиле вы можете добавить свои сборки.

## Технологии ##

Бэкенд написан на python и flask.
База данных - sqlalchemy.
Фронтенд html css.


## API ##

#### http://45.156.25.91/api [GET] – запрос который выдает список json всех сборок со всеми комплектующими
#### http://45.156.25.91/api [POST] – запрос который принимает json для быстрого добавления сборки в базу данных
#### http://45.156.25.91/api/<configuration_id> [get] – запрос который  выдает полную информацию о сборке в json виде


## Критерии к POST запросу ##

    'name': Обязательный,
    'about': Не Обязательный, 
    'cooler': Обязательный, 
    'cooler_link': Не Обязательный,
    'cooler_price': Обязательный, 
    'frame': Обязательный, 
    'frame_link': Не Обязательный,
    'frame_price': Обязательный,
    'ssd': Обязательный, 
    'ssd_link': Не Обязательный, 
    'ssd_price': Обязательный, 
    'cpu': Обязательный, 
    'cpu_link': Не Обязательный, 
    'cpu_price': Обязательный, 
    'power': Обязательный, 
    'power_link': Не Обязательный,
    'power_price': Обязательный,
    'motherboard': Обязательный, 
    'motherboard_link': Не Обязательный, 
    'motherboard_price': Обязательный,
    'gpu': Обязательный, 
    'gpu_link': Не Обязательный, 
    'gpu_price': Обязательный,
    'ram': Обязательный, 
    'ram_link': Не Обязательный, 
    'ram_price': Обязательный,
    'comment': Не Обязательный, 