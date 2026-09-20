<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3fz42bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d3fz42bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cockpit" {...props}></Icon>
