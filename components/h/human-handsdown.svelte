<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xssxl197b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xssxl197b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:human-handsdown" {...props}></Icon>
