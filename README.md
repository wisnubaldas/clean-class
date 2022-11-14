# Clean Class

Bikin class modul di laravel, biar rapih penggunaan dan terstruktur bikin aplikasinya :)

Sebelom install masukin script ini di file ``composer.json``


```json
"post-package-install": [
		"Wisnubaldas\\CleanClass\\BootScript::postPackageInstall"
],

```

Ini akan dijalankan ketika pertama kali packet di install, Modul ini jalan di laravel consol, buka terminal console project 

```php artisan make:domain {nama_class_nya}```

command diatas akan membuat class file dan interface di folder Domain, 
gunakan option ```-E {nama_class_extend_nya}``` jika ingin membuat class extend

```php artisan make:driver {nama_trait_nya}```

command diatas akan membuat file trait di folder Driver

```php artisan make:repositories {nama_class_nya}```

command ini akan membuat file class di folder Repositories

```php artisan make:usecase {nama_class_nya}```

command diatas akan membuat class file dan interface di folder UseCase, 
gunakan option ```-E {nama_class_extend_nya}``` jika ingin membuat class extend


