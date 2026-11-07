<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb1rgbcrq.css';
import '../../css/r/rihb8_rrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yb1rgbcrq"/><path class="rihb8_rrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paperclip-2-bold-duotone" {...props}></Icon>
