<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdkgl-bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zdkgl-bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:double-chevron-end-rtl" {...props}></Icon>
