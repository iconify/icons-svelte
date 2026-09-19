<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofy1pmhsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofy1pmhsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:facebook" {...props}></Icon>
