<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nc9fl6b0t.css';
import '../../css/k/krddiybmx.css';
import '../../css/f/fv6kukroi.css';
import '../../css/e/euj49csjz.css';
import '../../css/t/t5_54pbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nc9fl6b0t wm-k"/><path class="krddiybmx wm-a"/><path class="fv6kukroi wm-shadow"/><path class="euj49csjz wm-k"/><path class="t5_54pbtg wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:id-card-engrave" {...props}></Icon>
