<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m7qg3-bpx.css';
import '../../css/d/dzqxdrujv.css';
import '../../css/q/qebiyxk2a.css';
import '../../css/l/lbjpe_b5s.css';
import '../../css/e/e7-jbub5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m7qg3-bpx"/><path class="dzqxdrujv"/><path class="qebiyxk2a"/><path class="lbjpe_b5s"/><path class="e7-jbub5h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:drill" {...props}></Icon>
