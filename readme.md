Консоль запросов 9000 версии 1.1.8 (в разработке)

Для работы с этой консолью необходима версия платформы не ниже 8.3.12.
Режим совместимости возможен, начиная с 8.3.8.

Возможности:

- базовый функционал (редактирование запросов, исполнение, сохранение в файл, работа с параметрами, и т.д.)
- полноценная работа в режиме управляемых форм в режиме толстого и тонкого клиента
- поддержка всех типов 1С, в том числе момента времени, границы, уникального идентификатора, типа «Тип», вида движений, таблиц значений (табличные части), и т.д.
- поддержка списков, массивов, таблиц значений в параметрах, удобное их редактирование
- перехват любых запросов из отладчика вместе с параметрами и временными таблицами
- возможность получения всех результатов запроса («ВыполнитьПакет»)
- просмотр перехваченных временных таблиц, изменение их данных для отладки запроса
- перехват через функцию БСП ЗапросВСтрокуXML
- вывод результата в виде таблицы, дерева, а так же в табличный документ
- работает при запрете синхронных методов (использует только асинхронные методы клиента)
- отладка запросов, получающих большое количество данных: два варианта ограничения количества строк в режиме отладки
- сохранение комментариев в запросах после конструктора
- запоминает последний  файл, с которым производилась работа
- просмотр временных таблиц, формируемых запросом
- перехват фоновых и регламентных заданий, в том числе, запущенных под другим пользователем
- получение в результате запроса уникальных идентификаторов ссылок
- вставка предопределенных значений
- передача результата запроса в параметрами
- генерация текста запроса для создания временной таблицы из таблицы-параметрами
- обработка результата запроса кодом
- генерация кода на встроенном языке для исполнения запроса (с параметрами)
