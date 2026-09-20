<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0xv2tbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0xv2tbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chevron-right-2" {...props}></Icon>
