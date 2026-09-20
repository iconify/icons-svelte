<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnzi1zb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnzi1zb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-flash" {...props}></Icon>
