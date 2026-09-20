<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cly2z6b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cly2z6b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:device-vibrate" {...props}></Icon>
