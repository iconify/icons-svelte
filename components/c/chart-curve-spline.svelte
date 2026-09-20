<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpcjoqb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zpcjoqb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chart-curve-spline" {...props}></Icon>
