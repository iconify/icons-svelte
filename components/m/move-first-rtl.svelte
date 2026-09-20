<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_ckmcczc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r_ckmcczc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:move-first-rtl" {...props}></Icon>
