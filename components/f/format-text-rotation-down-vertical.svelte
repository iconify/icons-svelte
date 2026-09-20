<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxh8pobme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxh8pobme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-text-rotation-down-vertical" {...props}></Icon>
