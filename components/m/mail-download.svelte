<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wbvx8-9op.css';
import '../../css/w/wdve1s0yd.css';
import '../../css/t/ta7_a93uk.css';
import '../../css/e/eoh5b_aej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="wbvx8-9op"/><path class="wdve1s0yd"/><path class="ta7_a93uk"/><path class="eoh5b_aej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:mail-download" {...props}></Icon>
