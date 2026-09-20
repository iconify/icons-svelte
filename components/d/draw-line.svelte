<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6eio6bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6eio6bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:draw-line" {...props}></Icon>
