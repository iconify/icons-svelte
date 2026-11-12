<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snv2imbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="snv2imbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:graphhopper-dark" {...props}></Icon>
