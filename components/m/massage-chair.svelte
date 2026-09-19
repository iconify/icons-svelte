<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/axw7lr55v.css';
import '../../css/p/p1lghbcur.css';
import '../../css/q/qy_wc_bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="axw7lr55v"/><path class="p1lghbcur"/><path class="qy_wc_bod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:massage-chair" {...props}></Icon>
