<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq6w5q5vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="zq6w5q5vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-horizontal-stipple-left" {...props}></Icon>
