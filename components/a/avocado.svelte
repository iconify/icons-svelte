<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uppb44qmx.css';
import '../../css/b/bmbc7qb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uppb44qmx"/><ellipse class="bmbc7qb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:avocado" {...props}></Icon>
