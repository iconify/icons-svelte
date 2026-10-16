<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rid_tie-o.css';
import '../../css/m/mm9-oj8-f.css';
import '../../css/l/lu5-5ac7f.css';
import '../../css/n/nf6z_ngnm.css';
import '../../css/i/i59g4cbwi.css';
import '../../css/h/hbyn988mt.css';
import '../../css/m/mlgizs1di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rid_tie-o"/><path class="mm9-oj8-f"/><path class="lu5-5ac7f"/><path class="nf6z_ngnm"/><path class="i59g4cbwi"/><path class="hbyn988mt"/><path class="mlgizs1di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:neural-network-48-bold" {...props}></Icon>
