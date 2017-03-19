# Weekly Talks digest, week 9

February 27 - March 5

## Митап

В среду прошёл митап на тему _Node.js for IoT_, на котором речь шла о первых
шагах в использовании Node.js для программирования Arduino. Были рассмотрены
Johnny-Five, Node-RED и fritzing.

[Событие][] собрало порядка сорока человек. Встречу открыл [Павел Заяц][]. Он
продемонстрировал своего колёсного робота, с камерой и пространственными
сенсорами, построенного на Arduino. Робот управлялся со смартфона и
транслировал свой _взгляд_ на экран проектора.

[Событие]: https://www.facebook.com/events/157821608061410/
[Павел Заяц]: https://vk.com/ded_c_balalaikoi

[Павел Зубков][] (только осваивающий навыки построения роботов), по горячим
следам свего опыта, представил доклад о первых шагах в мире Arduino. Основной
тезис доклада: доступность Arduino, простота _starter kits_ и широкий
инструментарий Node.js позволяют учиться программировать устройства для
_интернета вещей_ не имея специальной подготовки.

[Павел Зубков]: https://www.facebook.com/pavel.zubkou

[Слайды основного доклада][slides] доступны на Google Docs. Первая часть,
повествующая о личной истории любопытства к радиоэлектронике, доступна только
в картинках. Сопроводительная история, это тот бонус, который получают только
участники живой встречи ;)

[slides]: https://docs.google.com/presentation/d/14yaGIR_gkd2sT4VOl6PqSuc3PYE6dqnqIH55MjQXWLA

Следом шла обзорно-практическая часть, которая
закончилась примером построения цепочки в среде Node-RED: от физического
соединения Arduino и джойстика до программирование ввода с джойскика
приводящего к запуску браузера, контролируемого через WebDriver.

---

Первые шаги в мир Arduino это только начало истории. Она была бы не полной без
опыта тех, кто уже прошёл не одну веху программируя микроконтроллеры. Своим
опытом и знаниями делились [Денис Антоник][], [Юрий Заяц][] и
[Александр Пузыня][].

[Денис Антоник]: https://vk.com/id6887066
[Юрий Заяц]: https://www.facebook.com/yury.zayats.1
[Александр Пузыня]: https://www.facebook.com/profile.php?id=100001527677861

Не потерять контакты, обсудить интересующие вопросы и последние новости поможет
Slack сообщества Weekly Talks. Канал [#arduino][] является общим для тем
_Internet of things_, программирования микроконтроллеров, Arduino и иных
устройств (см. [_Как подключиться к Slack каналам Weekly Talks_][how-to-slack]).

[how-to-slack]: ../how-to-slack.md

---

В завершение встречи, [Александр Пузыня][] рассказал о своём опыте с Arduino,
Netduino и ESP8266. Вот некоторые из вещей, о которых шла речь:

- https://en.wikipedia.org/wiki/Netduino
- https://www.espruino.com/
- https://en.wikipedia.org/wiki/NodeMCU
- https://mongoose-os.com/ (ранее известная как Smart.js for ESP8266)
  - https://github.com/cesanta/mongoose-os
- https://esp8266.ru/ - русское сообщество разработчиков на esp8266

## Slack digest

Основное за неделю из публичных каналов в _Weekly Talks_ Slack.

- У Weekly Talks теперь есть канал [#announcements][] в котором будут только
  анонсы и ничего кроме анонсов ;)
- По результатам митапа был создан обобщённый канал [#arduino][], который не
  только об Arduino, но и обо всём вокруг IoT.
- @yarik принёс в [#random][] интересный новый проект, [Broid][], дающий
  унифицированный интерфейс работы с мессенджерами, что может быть интересно
  для программирования чат-ботов.
- лента [#nodejs-newsroom][] рассказала о двух новых релизах Node.js 7.7.0 и
  7.7.1; и принесла обзорную статью о новых возможностях
  [диагностики Node.js][diag]

[#announcements]: https://weekly-talks.slack.com/messages/announcements/
[#arduino]: https://weekly-talks.slack.com/messages/arduino/
[#random]: https://weekly-talks.slack.com/messages/random/
[#nodejs-newsroom]: https://weekly-talks.slack.com/messages/nodejs-newsroom/
[Broid]: https://github.com/broidHQ/integrations
[diag]: https://nodejs.org/en/blog/wg/diag-wg-update-2017-02/

У вас ещё нет аккаунта Weekly Talks? см. [_Как подключиться к Slack каналам Weekly Talks_][how-to-slack]
