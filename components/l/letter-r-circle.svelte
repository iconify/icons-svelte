<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlty2ozxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlty2ozxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-r-circle" {...props}></Icon>
