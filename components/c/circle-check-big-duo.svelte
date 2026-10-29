<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/oan3fnbps.css';
import '../../css/c/cym073bex.css';
import '../../css/l/ly5598bwp.css';
import '../../css/u/ucexqlbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="oan3fnbps"/><path class="cym073bex"/><path class="ly5598bwp wm-a"/><path class="ucexqlbld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-check-big-duo" {...props}></Icon>
