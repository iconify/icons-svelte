<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxm6s-w5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mxm6s-w5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-cloud-light" {...props}></Icon>
