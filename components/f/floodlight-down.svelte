<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2pdpz74h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2pdpz74h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floodlight-down" {...props}></Icon>
