<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyovyz5ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyovyz5ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:network-strength-off-outline" {...props}></Icon>
