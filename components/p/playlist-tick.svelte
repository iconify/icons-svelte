<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sla533brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sla533brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:playlist-tick" {...props}></Icon>
