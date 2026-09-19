<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyxl8dbgf.css';
import '../../css/b/buduld4sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uyxl8dbgf"/><path class="buduld4sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-add" {...props}></Icon>
