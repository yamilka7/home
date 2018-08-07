# FAQ Final
#
#What do i expect when I visit the FAQ site?
FAQ site is dedicated to users
1.	As a user, I can create questions.
2.	As a user, I can answer questions
3.	As a user, I can edit questions/answers.
4.	As a user, I can delete questions/answers

#To run the FAQ project:
1.	git clone https://github.com/yamilka7/home
2.	CD into FAQ and run composer install
3.	cp .env.example to .env
4.	run: php artisan key:generate
5.	setup database / with sqlite or other https://laravel.com/docs/5.6/database
6.	Run: php artisan migrate
7.	Run: unit tests: phpunit
8.	Run: seeds php artisan migrate:refresh --seed

#Prerequisites:
You need to complete up to video 20 where it has testing to begin this project, if you don't have previous experience with Laravel.
https://laracasts.com/series/laravel-from-scratch-2017

#Relevant Laravel Resources:
https://laravel.com/docs/5.6/eloquent
https://laravel.com/docs/5.6/database
https://laravel.com/docs/5.6/seeding
https://laravel.com/docs/5.6/testing

#New Feature Added:
1.Added a notification button
