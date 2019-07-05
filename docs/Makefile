
deploy:
	rm -rf _site
	rm -rf docs
	bundle exec jekyll build
	mv _site docs
	git add .
	git commit -m "add: contents `date`"
	git push origin master
