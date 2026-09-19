<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rvsc-bbld.css';
import '../../css/i/iinkstb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":39,"height":32};
const content = `<g class="cuyn6tgcc"><path class="rvsc-bbld"/><path class="iinkstb0q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:desktop" {...props}></Icon>
