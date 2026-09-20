<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4bctp2ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e4bctp2ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bars" {...props}></Icon>
