<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfbjn0b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfbjn0b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gradienter-line" {...props}></Icon>
