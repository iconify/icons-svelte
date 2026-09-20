<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyq91rbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyq91rbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:device-laptop" {...props}></Icon>
