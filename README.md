# laravel-toolkit

A collection of reusable Laravel traits, utilities, and extensions for building applications faster.

## Features

* Cacheable models and data
* Activity logging integration
* Searchable models
* More reusable Laravel components coming soon

## Installation

Install the package via Composer:

```bash
composer require zerexei/laravel-toolkit
```

## Usage

### Cacheable

Add caching support to your model or class:

```php
use Zerexei\LaravelToolkit\Traits\Cacheable;

class Post extends Model
{
    use Cacheable;
}
```

### HasActivityLogs

Add activity logging support using Spatie Activity Log:

```php
use Zerexei\LaravelToolkit\Traits\HasActivityLogs;

class User extends Model
{
    use HasActivityLogs;
}
```

### Searchable

Add searchable functionality:

```php
use Zerexei\LaravelToolkit\Traits\Searchable;

class Post extends Model
{
    use Searchable;
}
```

## Requirements

* PHP 8.2+
* Laravel 11+
* `spatie/laravel-activitylog`

## Package Information

```json
{
  "name": "zerexei/laravel-toolkit",
  "description": "Laravel toolkit containing reusable traits, helpers, and extensions",
  "license": "MIT"
}
```

## Roadmap / TODO (MVP)

The following features are planned for future releases:

### Traits

* [x] `Cacheable` — Add caching support for models and data
* [x] `HasActivityLogs` — Integrate activity logging with Spatie Activity Log
* [x] `Searchable` — Add simple model searching capabilities
* [ ] `HasUuid` — UUID support for models
* [ ] `HasSlug` — Automatic slug generation
* [ ] `HasStatus` — Model status management helpers
* [ ] `HasPermissions` — Reusable permission handling
* [ ] `HasMedia` — Common media/file attachment helpers
* [ ] `HasFilters` — Reusable query filtering support

### Utilities

* [ ] String manipulation helpers
* [ ] Array manipulation helpers
* [ ] Date/time helpers
* [ ] Common Laravel validation helpers

### Eloquent Enhancements

* [ ] Query builder macros
* [ ] Model scopes collection
* [ ] Relationship helpers
* [ ] Model event utilities

### Developer Experience

* [ ] Artisan commands for package setup
* [ ] Configuration publishing
* [ ] Better documentation and examples
* [ ] Test coverage improvements

## Long-Term Goals

* Keep the package lightweight and framework-friendly
* Provide reusable components for common Laravel application patterns
* Avoid unnecessary dependencies while improving developer productivity


## License

The MIT License (MIT).
