<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/n/nagtiqban.css';
import '../../css/t/to2zchgfu.css';
import '../../css/c/cswwhib7x.css';
import '../../css/x/xjdiaqb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="nagtiqban"/><circle class="to2zchgfu"/><circle class="cswwhib7x"/><circle class="xjdiaqb1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:blockchain" {...props}></Icon>
