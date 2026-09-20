<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voxoyd1yc.css';
import '../../css/y/ys14dvbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voxoyd1yc"/><path clip-rule="evenodd" class="ys14dvbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bft" {...props}></Icon>
