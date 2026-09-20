<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw1b53b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw1b53b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-h-circle" {...props}></Icon>
