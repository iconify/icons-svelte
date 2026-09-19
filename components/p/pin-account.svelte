<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7ipbbrfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":456};
const content = `<path class="q7ipbbrfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:pin-account" {...props}></Icon>
