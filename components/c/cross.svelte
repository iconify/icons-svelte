<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh4g1sb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="zh4g1sb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cross" {...props}></Icon>
