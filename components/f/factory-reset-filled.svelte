<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcyyobc0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dcyyobc0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:factory-reset-filled" {...props}></Icon>
