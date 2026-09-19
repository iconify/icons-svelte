<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e39ud6bwf.css';
import '../../css/r/rhygotbxm.css';
import '../../css/d/d_xxxv6_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="e39ud6bwf"/><path class="rhygotbxm"/><path class="d_xxxv6_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cube-view" {...props}></Icon>
