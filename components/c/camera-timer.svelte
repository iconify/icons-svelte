<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvycvgblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvycvgblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-timer" {...props}></Icon>
