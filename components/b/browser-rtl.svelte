<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m66w98bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m66w98bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:browser-rtl" {...props}></Icon>
