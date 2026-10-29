<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l1pv_sbbk.css';
import '../../css/r/ra2whvb7t.css';
import '../../css/i/iz66ytb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l1pv_sbbk wm-k"/><path class="ra2whvb7t wm-k"/><path class="iz66ytb_v wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:regex-sketch" {...props}></Icon>
