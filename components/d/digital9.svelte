<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9pd17xhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="d9pd17xhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:digital9" {...props}></Icon>
