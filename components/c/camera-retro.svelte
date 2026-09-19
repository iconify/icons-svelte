<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzlu99b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzlu99b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:camera-retro" {...props}></Icon>
