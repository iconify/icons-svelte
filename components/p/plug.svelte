<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/s/sf-1gtb_i.css';
import '../../css/n/n0fv11e2r.css';
import '../../css/k/kvhkc1b3j.css';
import '../../css/i/ig1-7b7uv.css';
import '../../css/o/o95lhhbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="sf-1gtb_i"/><path class="n0fv11e2r"/><path class="kvhkc1b3j"/><path class="ig1-7b7uv"/><path class="o95lhhbaw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:plug" {...props}></Icon>
