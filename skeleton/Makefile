dev:
	export APP_SETTINGS="project.config.DevelopmentConfig"; \
python manage.py runserver -h 0.0.0.0

install:
	sudo apt-get install nodejs

run:
	python manage.py runserver -h 0.0.0.0

test: clean
	python manage.py test

cov:
	python manage.py cov

clean:
	if [ -f project/test.sqlite ]; then rm project/test.sqlite; fi
