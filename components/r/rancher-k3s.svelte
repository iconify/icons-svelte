<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og5h33zgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="og5h33zgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-k3s" {...props}></Icon>
