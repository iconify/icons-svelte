<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y33_9cd0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y33_9cd0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:directions-bike" {...props}></Icon>
