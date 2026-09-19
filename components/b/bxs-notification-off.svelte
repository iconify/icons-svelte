<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h68a5vtzz.css';
import '../../css/x/xb9s9cbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="h68a5vtzz"/><path class="xb9s9cbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-notification-off" {...props}></Icon>
