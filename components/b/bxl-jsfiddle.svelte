<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr2-x0j6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2-x0j6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-jsfiddle" {...props}></Icon>
