## Дипломный проект. Задание 2: веб-приложение

### Автотесты для проверки программы, которая помогает заказать бургер в Stellar Burgers

### Реализованные сценарии

Созданы тесты для веб-приложения, покрывающие классы `BasicFunctionality`, `LoginPage`, `MainPage`, `OrderFeedPage`,`PasswordRecoveryPage`,`ProfilePage`.

Сделан Allure-отчёт (отчёт: http://192.168.100.10:59134/index.html)

### Структура проекта

- `locators` - папка, содержащая локаторы.
- `tests` - пакет, содержащий тесты, разделенные по классам. Например, `test_basic_functionality.py`, `test_order_feed.py` и т.д.
- `page_objects` - пакет, содержащий объекты страниц.

### Запуск автотестов

**Установка зависимостей**

> `pip install -r requirements.txt`/ `py -m pip install -r requirements.txt`

**Запуск автотестов и создание Allure-отчёта**

>  `pytest --alluredir=allure_results`/ `py -m pytest --alluredir=allure_results`
>  `allure serve allure_results`/ `py -m allure serve allure_results`
# Diplom_2
