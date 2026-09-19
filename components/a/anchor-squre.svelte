<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e9bm3i9jh.css';
import '../../css/t/trdpk-b6y.css';
import '../../css/l/lpi2p7bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="e9bm3i9jh"/><circle class="trdpk-b6y"/><path class="lpi2p7bmg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:anchor-squre" {...props}></Icon>
