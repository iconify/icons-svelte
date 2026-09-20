<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k203-ju_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k203-ju_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:canoe-on-station-wagon" {...props}></Icon>
