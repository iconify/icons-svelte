<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/llper-sbd.css';
import '../../css/i/idq3xvbyd.css';
import '../../css/m/meq82tc7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="llper-sbd"/><path class="idq3xvbyd"/><path class="meq82tc7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:restart-duotone" {...props}></Icon>
