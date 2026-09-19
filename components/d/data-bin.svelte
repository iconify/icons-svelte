<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvvss987d.css';
import '../../css/p/p5oy8duvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gvvss987d"/><path class="p5oy8duvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-bin" {...props}></Icon>
