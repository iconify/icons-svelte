<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwja3t83w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwja3t83w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bookmark-music-outline" {...props}></Icon>
