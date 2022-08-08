## Steps to reproduce bug

```
composer install
DB_CONNECTION=sqlite DB_DATABASE=:memory: php artisan migrate
```
