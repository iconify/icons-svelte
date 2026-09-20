<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvdp7_lgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvdp7_lgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-plug-off" {...props}></Icon>
