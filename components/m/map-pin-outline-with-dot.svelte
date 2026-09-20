<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gys_s0bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gys_s0bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:map-pin-outline-with-dot" {...props}></Icon>
