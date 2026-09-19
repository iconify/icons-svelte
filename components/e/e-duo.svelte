<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyl55v84k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="zyl55v84k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:e-duo" {...props}></Icon>
