<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz3z958ur.css';
import '../../css/n/nxwcidc1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uz3z958ur"/><path class="nxwcidc1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:manifest-light" {...props}></Icon>
