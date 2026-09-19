<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8893zazi.css';
import '../../css/k/k-2_-zb2s.css';
import '../../css/a/aw-an9zor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x8893zazi"/><path class="k-2_-zb2s"/><path class="aw-an9zor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:outlook-severe" {...props}></Icon>
