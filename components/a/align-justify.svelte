<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vze09sf9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vze09sf9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-justify" {...props}></Icon>
