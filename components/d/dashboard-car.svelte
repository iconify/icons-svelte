<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/b/b7e_qlv_s.css';
import '../../css/p/p0mk-tbae.css';
import '../../css/d/d51vjtaux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="b7e_qlv_s"/><path class="p0mk-tbae"/><path clip-rule="evenodd" class="d51vjtaux"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:dashboard-car" {...props}></Icon>
