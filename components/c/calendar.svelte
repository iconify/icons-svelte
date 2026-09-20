<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke399mbnc.css';
import '../../css/f/fpxrp_bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ke399mbnc"/><path class="fpxrp_bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:calendar" {...props}></Icon>
