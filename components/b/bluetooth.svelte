<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd3h-8q2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd3h-8q2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:bluetooth" {...props}></Icon>
