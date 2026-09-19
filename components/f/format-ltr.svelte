<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_aohhbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="j_aohhbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-ltr" {...props}></Icon>
