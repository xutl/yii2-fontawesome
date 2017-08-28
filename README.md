适用于 Yii2 的 Font Awesome字体
==============================

安装
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require --prefer-dist xutl/yii2-fontawesome-asset
```

or add

```json
"xutl/yii2-fontawesome-asset": "~2.0.0"
```

to the `require` section of your `composer.json`.

````
\xutl\fontawesome\Asset::register($this);
````

### Use CDN

```php
'components' => [
    'assetManager' => [
        'bundles' => [
            'xutl\fontawesome\Asset' => [
                'sourcePath' => null, // do not publish the bundle
                'css' => [
                    '//cdn.bootcss.com/font-awesome/4.7.0/css/font-awesome.min.css',
                ]
            ]
        ]
    ],
],


```
