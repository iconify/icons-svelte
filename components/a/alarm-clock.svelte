<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/u/uc806cc_b.css';
import '../../css/r/rp0tc0bpg.css';
import '../../css/f/fmadhnbwi.css';
import '../../css/o/o0qcwtbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="uc806cc_b"/><path class="rp0tc0bpg"/><path class="fmadhnbwi"/><path class="o0qcwtbtl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:alarm-clock" {...props}></Icon>
