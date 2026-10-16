<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfnsa8bub.css';
import '../../css/a/a8jgx4b9e.css';
import '../../css/x/xw8v0ibsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rfnsa8bub"/><path class="a8jgx4b9e"/><path class="xw8v0ibsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-canopy-20-bold" {...props}></Icon>
