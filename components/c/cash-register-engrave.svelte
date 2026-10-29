<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mkh_6h2do.css';
import '../../css/m/majtcdc7y.css';
import '../../css/m/mvtddkbrz.css';
import '../../css/q/qlkgjzbfl.css';
import '../../css/g/ghy1agb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mkh_6h2do wm-k"/><path class="majtcdc7y wm-a"/><path class="mvtddkbrz wm-shadow"/><path class="qlkgjzbfl wm-k"/><path class="ghy1agb1b wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cash-register-engrave" {...props}></Icon>
