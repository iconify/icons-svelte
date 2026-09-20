<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6la5k3mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6la5k3mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-fit" {...props}></Icon>
