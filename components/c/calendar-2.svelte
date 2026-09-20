<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfrsz9bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfrsz9bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-2" {...props}></Icon>
