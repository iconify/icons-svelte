<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/p/ph1s97tzl.css';
import '../../css/y/yh4fy_bgb.css';
import '../../css/t/tpngvrbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><rect class="ph1s97tzl"/><path class="yh4fy_bgb"/></g><circle class="tpngvrbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:image-stroke-16" {...props}></Icon>
