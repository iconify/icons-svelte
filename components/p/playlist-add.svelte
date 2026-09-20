<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe3g_bcxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe3g_bcxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:playlist-add" {...props}></Icon>
