<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/y/yk5i701wb.css';
import '../../css/p/ptkmnzomc.css';
import '../../css/b/brx-gnbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="h01tyzbfu"><path class="yk5i701wb"/><path class="ptkmnzomc"/><path class="brx-gnbny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:donut" {...props}></Icon>
