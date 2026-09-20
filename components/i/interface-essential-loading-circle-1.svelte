<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2p99079n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e2p99079n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-loading-circle-1" {...props}></Icon>
