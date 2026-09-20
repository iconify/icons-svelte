<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zydp2p7fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zydp2p7fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:receipt-wrangler-light" {...props}></Icon>
