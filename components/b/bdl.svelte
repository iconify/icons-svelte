<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wglng-x4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wglng-x4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bdl" {...props}></Icon>
