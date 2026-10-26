<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vd1zo2b8e.css';
import '../../css/r/rspme6bbw.css';
import '../../css/v/vs-o0_phq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="vd1zo2b8e"/><path class="rspme6bbw"/><path class="vs-o0_phq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:heat-therapy" {...props}></Icon>
