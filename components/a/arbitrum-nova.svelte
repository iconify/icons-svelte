<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjpbtbv7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjpbtbv7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:arbitrum-nova" {...props}></Icon>
