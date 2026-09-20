<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0fn58bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w0fn58bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:d-and-d" {...props}></Icon>
