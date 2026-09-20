<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fghn1n5gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fghn1n5gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:football-ball-solid" {...props}></Icon>
