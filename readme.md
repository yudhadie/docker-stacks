#Jika composer install error
chmod -R 775 /var/www/projects/laravel-app
chown -R 33:33 /var/www/projects/laravel-app

##DB Mysql
DB_CONNECTION=mysql
DB_HOST=shared-mysql
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=rootpassword123
