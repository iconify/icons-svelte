<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp7mpy2fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lp7mpy2fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bishops-miter-with-latin-cross-beside-crozier-head" {...props}></Icon>
