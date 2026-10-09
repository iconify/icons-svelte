<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncjlt0bzz.css';
import '../../css/r/rvuq3ibhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ncjlt0bzz"/><path class="rvuq3ibhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dollar-20" {...props}></Icon>
