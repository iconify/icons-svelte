<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyxl8dbgf.css';
import '../../css/a/arfms3bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uyxl8dbgf"/><path class="arfms3bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:intent-request-create" {...props}></Icon>
