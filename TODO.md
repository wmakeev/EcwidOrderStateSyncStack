# TODO

- [ ] Подумать как лучше работать с переменными окружения и конфигурацией

  Часть переменных окружения заданы изначально, часть задаются после чтения секретов.
  Аналогично идет чтение JSON конфига.

  Проблема в том, что конфигурация переменных окружения при старте и после инициализации отличается. Может быть не стоит неявно задавать переменные окружения, а отправлять их в объект конфига.