<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkcw5h-pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkcw5h-pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:device-tv" {...props}></Icon>
