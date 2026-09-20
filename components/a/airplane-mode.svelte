<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1n2kmv4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h1n2kmv4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:airplane-mode" {...props}></Icon>
