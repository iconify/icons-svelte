<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmpwscv4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmpwscv4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bulb-multiple-off" {...props}></Icon>
