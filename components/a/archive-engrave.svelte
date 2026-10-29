<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/iaoyh7gpi.css';
import '../../css/q/q511u5m8e.css';
import '../../css/k/k_lneb11t.css';
import '../../css/o/oy6a688zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="iaoyh7gpi wm-k"/><path class="q511u5m8e wm-shadow"/><path class="k_lneb11t wm-k"/><path class="oy6a688zn wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:archive-engrave" {...props}></Icon>
