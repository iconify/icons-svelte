<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3jp_r57s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="w3jp_r57s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:clone" {...props}></Icon>
