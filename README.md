# Привет, я Иван 👋

**Python-разработчик** из Краснодара, студент КубГТУ (программная инженерия) и
самозанятый. Делаю Telegram-боты на aiogram 3, ИИ-ассистентов с RAG, парсеры и
автоматизацию, десктопные программы на Qt. Первый коммерческий бот написал в 15 лет,
с тех пор все проекты веду сам: от постановки задачи до деплоя и поддержки

Ниже только то, что можно открыть и посмотреть в коде

## 📫 Контакты

- **Email:** xvin240@gmail.com
- **Telegram:** [@xvin84](https://t.me/xvin84)
- **Kwork:** [kwork.ru/user/xvin](https://kwork.ru/user/xvin)
- **Город:** Краснодар (UTC+3), работаю удалённо

---

## 🤖 Telegram-боты

- **[appointment-bot](https://github.com/xvin84/appointment-bot)** - запись клиентов
  в пару нажатий: услуга, день, свободный слот, подтверждение. Админ-панель прямо
  в боте, напоминания перед визитом, логика слотов покрыта тестами
- **[rag-faq-bot](https://github.com/xvin84/rag-faq-bot)** - бот поддержки, который
  отвечает по вашей базе знаний со ссылкой на источник, а если ответа там нет,
  честно говорит «не знаю» вместо выдумки
- **[AlmaTrack](https://github.com/xvin84/AlmaTrack)** 🥇 - платформа учёта
  трудоустройства студентов, **1 место на хакатоне**. Бот на aiogram 3 + FastAPI +
  Flask-админка + SQLAlchemy. *Моя часть: бот и бэкенд-API*
- **[truth-or-dare-bot](https://github.com/xvin84/truth-or-dare-bot)** - многопользовательская
  игра: комнаты, ходы по таймеру, фильтры заданий, PostgreSQL + Redis, Alembic

## 🧠 ИИ и RAG

- **[legal-ai-assistant-case-study](https://github.com/xvin84/legal-ai-assistant-case-study)** -
  разбор архитектуры боевого бота юридических консультаций для Telegram и MAX: RAG
  на pgvector, сценарии с генерацией DOCX, фоновые задачи на arq, оплата,
  FastAPI-админка
- **[pgvector-rag](https://github.com/xvin84/pgvector-rag)** - async RAG-тулкит поверх
  PostgreSQL + pgvector: чанкинг по заголовкам, косинусный поиск с весами документов
  и порогом релевантности, HNSW-индекс

## 🕷 Парсинг и автоматизация

- **[site-watcher](https://github.com/xvin84/site-watcher)** - следит за любой страницей
  со списком (каталог, доска объявлений, выдача) и присылает новые позиции в Telegram.
  CSS-селекторы в конфиге, тихий первый прогон, запуск по cron
- **[TotalBattleExchangeScanner](https://github.com/xvin84/TotalBattleExchangeScanner)** -
  программа, которая читает интерфейс браузерной игры и действует за пользователя.
  PyQt6, Chromium через Playwright, компьютерное зрение (OpenCV с перебором масштабов
  и **своя обученная модель YOLO**), мультиаккаунт с шифрованием, режим 24/7 в трее
- **[tk_btc_assistant](https://github.com/xvin84/tk_btc_assistant)** - автоматизация
  мобильной игры на Android через ADB: узнаёт экраны по шаблонам OpenCV, на незнакомом
  экране ничего не нажимает. Окно на PySide6, готовые сборки для Windows в Releases

## 🖥 Десктоп и железо

- **[Adalight](https://github.com/xvin84/Adalight)** - фоновая подсветка монитора
  светодиодной лентой: захват экрана на Windows (DXGI) и Linux/Wayland, прошивка
  для Arduino/ESP, по которой программа сама узнаёт плату и скорость порта, GUI на PySide6
  с живым превью, плагины и трей

## 🧰 Библиотеки

Вынесены из продакшена, под MIT, с тестами и CI:

- **[retry-aiohttp-session](https://github.com/xvin84/retry-aiohttp-session)** - сессия
  aiogram, которая повторяет запросы к Bot API при сетевых сбоях
- **[tg-max-identity](https://github.com/xvin84/tg-max-identity)** - единый аккаунт
  пользователя в Telegram и MAX по хешу телефона, резолвер NEW/LINKED/ALREADY/CONFLICT

## 📱 Мобильная разработка

- **[Palimpsest](https://github.com/xvin84/palimpsest)** - музыкальный плеер для
  Android и компьютера, в котором ничего не стирается: при перезаливке трека
  старая версия остаётся в истории. Своя медиатека работает офлайн, Яндекс
  Музыка и YouTube Music докачивают недостающее. Kotlin, Jetpack Compose, Media3,
  Room, публичная бета с видеообзором в Releases
- **[auto-assistant-case-study](https://github.com/xvin84/auto-assistant-case-study)** -
  офлайн-приложение «история автомобиля» на React Native / Expo + Supabase
  (PostgreSQL + RLS): синхронизация гостя в облако, напоминания, PDF-отчёты

## 📚 Учёба

- **[cpp-notes](https://github.com/xvin84/cpp-notes)** - мои конспекты курса C++ МФТИ,
  [опубликованы сайтом](https://xvin84.github.io/cpp-notes) на Quartz, сборка
  и деплой через GitHub Actions

## 🛠 Стек

- **Python async** · **aiogram 3** · **FastAPI** · **Flask** · **httpx** · **arq**
- **PostgreSQL** + **pgvector** · **Redis** · **SQLite** · **SQLAlchemy 2.0** · **Alembic**
- **OpenAI API / RAG** · Structured Outputs
- **Playwright** · **BeautifulSoup** · **OpenCV** · **YOLO** · ADB
- **PyQt6 / PySide6** · PyInstaller
- **Kotlin** · **Jetpack Compose** · Media3
- **React Native / Expo** · **Supabase** · **TypeScript**
- **Docker Compose** · **GitHub Actions** · **pytest** · `uv` · Linux

## 🔒 Закрытые проекты

Код под NDA, но архитектуру части из них я вынес в кейсы и библиотеки выше:

- **ИИ-бот юридических консультаций** - клиентский проект: оплата, RAG по
  нормативной базе с цитатами, фоновая обработка, деплой с учётом российских
  ограничений. Обезличенный разбор - в
  [legal-ai-assistant-case-study](https://github.com/xvin84/legal-ai-assistant-case-study)
- **Локальный ИИ для юриста** - установщик полностью офлайновой связки модели
  и базы документов: сам смотрит железо, подбирает модель под память видеокарты
  и оставляет инструкцию на рабочем столе
- **Бот интернет-магазина** - первый коммерческий заказ, работал с октября 2024
  по июнь 2025

## ⚙️ Как работаю

- Сначала разбираюсь в задаче и проверяю, что обещанное вообще выполнимо, потом называю срок
- Код с тестами и README, чтобы проект можно было передать другому разработчику
- Регулярно показываю промежуточный результат, а не пропадаю до дедлайна
- После сдачи помогаю с запуском и правками

---

## 📈 GitHub

![GitHub stats](https://github-readme-stats.vercel.app/api?username=xvin84&show_icons=true&theme=dark&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=xvin84&layout=compact&theme=dark)

**Открыт для заказов и работы** - фриланс, проектная занятость, стажировка или
частичная занятость удалённо. Пишите на xvin240@gmail.com или в
[Telegram](https://t.me/xvin84)
