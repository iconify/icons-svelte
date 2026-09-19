<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwns-mv1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="vwns-mv1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:network-warning" {...props}></Icon>
