<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxcl3kb-l.css';
import '../../css/y/y-7_m5bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zxcl3kb-l"/><path class="y-7_m5bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-generate" {...props}></Icon>
