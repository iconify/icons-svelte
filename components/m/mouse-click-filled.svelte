<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwkaotkvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dwkaotkvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mouse-click-filled" {...props}></Icon>
