Использование компонентов сессии
===========================

Для использования компонента `Session`, в дополнительных настройках соединения, как описано в разделе [Installation](installation.md),
вы должны настроить компонент `session` как `yii\mongodb\Session`:

```php
return [
    //....
    'components' => [
        // ...
        'session' => [
            'class' => 'yii\mongodb\Session',
        ],
    ]
];
```