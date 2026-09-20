<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrfqdcc-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xrfqdcc-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proxmox-light" {...props}></Icon>
