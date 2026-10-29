<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e8mhx6bnd.css';
import '../../css/h/hpjvobbts.css';
import '../../css/o/orupijbnu.css';
import '../../css/h/hnvjbpuwe.css';
import '../../css/g/gav9x_bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e8mhx6bnd wm-k"/><path class="hpjvobbts wm-a"/><path class="orupijbnu wm-shadow"/><path class="hnvjbpuwe wm-k"/><path class="gav9x_bhv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:log-in-engrave" {...props}></Icon>
