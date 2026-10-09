<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0y6ou17w.css';
import '../../css/m/ma9kh6yyc.css';
import '../../css/x/xd35sxcdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w0y6ou17w"/><path class="ma9kh6yyc"/><path class="xd35sxcdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:record-player-48" {...props}></Icon>
