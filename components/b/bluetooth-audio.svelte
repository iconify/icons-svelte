<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjku7rbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjku7rbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bluetooth-audio" {...props}></Icon>
