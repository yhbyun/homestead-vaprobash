# Vaprobash script for Laravel Homestead

`vaprobash.rb` is a modified [vaprobash](https://github.com/fideloper/Vaprobash)
script to work with [Laravel Homestead](http://laravel.com/docs/master/homestead).

The original idea came from the
[kaamaru/Homestead-Vaprobash-Scripts](https://github.com/kaamaru/Homestead-Vaprobash-Scripts).

## Installation

1. Add `vaprobash.rb` to the `homestead/scripts` directory
2. Unomment the scripts you'd like to run in `vaprobash.rb`.
3. Add the following to the end of the `Vagrantfile` in your homestead directory

```
require_relative 'scripts/vaprobash.rb'
```
