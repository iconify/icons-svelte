<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt4bjv1bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt4bjv1bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pin-off" {...props}></Icon>
