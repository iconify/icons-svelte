<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdit3bbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdit3bbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:monero-line" {...props}></Icon>
