<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0oiyblvd.css';
import '../../css/n/nxr9mlzqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i0oiyblvd"/><path class="nxr9mlzqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-epinio" {...props}></Icon>
