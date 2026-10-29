<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lmla34nnh.css';
import '../../css/s/stk13fbal.css';
import '../../css/s/suvv_lbra.css';
import '../../css/n/ni2pyrbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lmla34nnh wm-k"/><path class="stk13fbal wm-a"/><path class="suvv_lbra wm-k"/><path class="ni2pyrbla wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:fan-sketch" {...props}></Icon>
