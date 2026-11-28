<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc3-dh2aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yc3-dh2aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cookie-off" {...props}></Icon>
