<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5tv27bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t5tv27bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:network-wired-wireless" {...props}></Icon>
