<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_3do1bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_3do1bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:dark" {...props}></Icon>
