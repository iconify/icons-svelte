<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxk9_bc3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dxk9_bc3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:carousel-vertical" {...props}></Icon>
