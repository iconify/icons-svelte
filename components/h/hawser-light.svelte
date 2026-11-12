<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-2q8bc0s.css';
import '../../css/s/s4czx2bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-2q8bc0s"/><path class="s4czx2bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hawser-light" {...props}></Icon>
