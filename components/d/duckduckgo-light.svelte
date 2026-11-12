<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypknmkbto.css';
import '../../css/r/ra8213bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ypknmkbto"/><path class="ra8213bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:duckduckgo-light" {...props}></Icon>
