<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmex_vr6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmex_vr6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-submariner" {...props}></Icon>
