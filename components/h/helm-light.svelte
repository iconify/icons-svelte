<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyia3bbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iyia3bbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:helm-light" {...props}></Icon>
