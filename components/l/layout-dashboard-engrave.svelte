<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w4dem-b-z.css';
import '../../css/a/aogbohb-z.css';
import '../../css/o/ow8ez-lyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w4dem-b-z"/><path class="aogbohb-z wm-shadow"/><path class="ow8ez-lyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:layout-dashboard-engrave" {...props}></Icon>
