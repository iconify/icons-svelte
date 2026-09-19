<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/w/w50s6tb_z.css';
import '../../css/j/j57v_ccdv.css';
import '../../css/x/xxkl7ut0j.css';
import '../../css/n/no2x-xgpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="w50s6tb_z"/><path class="j57v_ccdv"/><path class="xxkl7ut0j"/><path class="no2x-xgpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:log" {...props}></Icon>
