<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur-idbj9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur-idbj9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:location-arrow-1" {...props}></Icon>
