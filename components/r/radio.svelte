<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3o4v_bul.css';
import '../../css/r/rdhxn-bpo.css';
import '../../css/r/r-40nkb-i.css';
import '../../css/t/tpc3akbba.css';
import '../../css/o/omcq-ibvt.css';
import '../../css/g/g_u53lnib.css';
import '../../css/u/ug2-tibnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m3o4v_bul"/><path class="rdhxn-bpo"/><path class="r-40nkb-i"/><path class="tpc3akbba"/><path class="omcq-ibvt"/><path class="g_u53lnib"/><path class="ug2-tibnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:radio" {...props}></Icon>
