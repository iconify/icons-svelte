<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/awv1y2bci.css';
import '../../css/t/tqb_6nb6c.css';
import '../../css/q/qx_afm4tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="awv1y2bci"/><circle class="tqb_6nb6c"/><path class="qx_afm4tr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:node-round" {...props}></Icon>
