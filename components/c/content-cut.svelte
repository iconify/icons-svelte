<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xja25sb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xja25sb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-cut" {...props}></Icon>
