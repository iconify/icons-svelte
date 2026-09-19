<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv2_vmbmc.css';
import '../../css/d/djk4s6bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zv2_vmbmc"/><path class="djk4s6bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:repo-source-code" {...props}></Icon>
