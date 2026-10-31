<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpi0bvd3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpi0bvd3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heart-pulse-round" {...props}></Icon>
