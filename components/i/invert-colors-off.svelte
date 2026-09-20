<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkm0tz84w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkm0tz84w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invert-colors-off" {...props}></Icon>
