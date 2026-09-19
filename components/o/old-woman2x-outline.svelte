<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ozp_01nrn.css';
import '../../css/n/nk5wt5brv.css';
import '../../css/r/rsrrjow2s.css';
import '../../css/n/n-nv5yscg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ozp_01nrn"/><path class="nk5wt5brv"/><path clip-rule="evenodd" class="rsrrjow2s"/><path class="n-nv5yscg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:old-woman2x-outline" {...props}></Icon>
