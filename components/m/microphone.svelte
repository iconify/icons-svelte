<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0z3-vbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="p0z3-vbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:microphone" {...props}></Icon>
