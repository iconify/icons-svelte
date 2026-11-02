<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdajw1bev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdajw1bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-sun-rain-line" {...props}></Icon>
