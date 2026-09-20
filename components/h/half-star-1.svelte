<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k78xr_h_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="k78xr_h_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:half-star-1" {...props}></Icon>
