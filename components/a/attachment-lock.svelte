<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq7tt2btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq7tt2btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:attachment-lock" {...props}></Icon>
