<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8x1q1cuv.css';
import '../../css/a/aw90g_bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c8x1q1cuv"/><path class="aw90g_bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:real-estate-building-ad" {...props}></Icon>
