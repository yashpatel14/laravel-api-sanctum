# 🔐 Laravel 12 API Authentication with Sanctum

A simple and secure Laravel 12 API that uses [Laravel Sanctum](https://laravel.com/docs/sanctum) for token-based authentication. This setup supports registration, login, logout, and retrieving authenticated user details.

---

## 🧰 Tech Stack

- Laravel 12
- Laravel Sanctum (API token authentication)
- MySQL/PostgreSQL/SQLite (any Laravel-supported DB)
- PHP 8.2+

---

## 🚀 Features

- User Registration
- Token-Based Login & Logout
- Authenticated User Endpoint (`/me`)
- Protect routes with `auth:sanctum` middleware
- Compatible with Postman, mobile apps, or JS frontends

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/laravel12-sanctum-api.git
cd laravel12-sanctum-api

### Install Dependencies

composer install

### Set Up Environment

cp .env.example .env
php artisan key:generate

### Run Migrations

### php artisan migrate


## 🔐 Sanctum Setup

### Install Sanctum

composer require laravel/sanctum

### Publish Sanctum Configuration

php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"

### Run Sanctum Migrations

php artisan migrate


