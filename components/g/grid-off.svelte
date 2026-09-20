<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi2p_hbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi2p_hbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:grid-off" {...props}></Icon>
