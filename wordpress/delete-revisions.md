```
DELETE a,b,c FROM wp_posts a LEFT JOIN wp_term_relationships b ON (a.ID=b.object_id) LEFT JOIN wp_postmeta c ON (a.ID=c.post_id) WHERE a.post_type='revision';
```
