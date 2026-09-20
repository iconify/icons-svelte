<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysq25cbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysq25cbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:location-2-line" {...props}></Icon>
