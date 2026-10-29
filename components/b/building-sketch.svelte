<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dwq1ipb-a.css';
import '../../css/y/y516q1b7t.css';
import '../../css/u/u79d_sb8z.css';
import '../../css/u/ugvm93m5y.css';
import '../../css/h/hqoal7mrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dwq1ipb-a"/><path class="wm-k y516q1b7t"/><path class="u79d_sb8z wm-a"/><path class="ugvm93m5y wm-k"/><path class="hqoal7mrj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:building-sketch" {...props}></Icon>
