<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m7_vfacpm.css';
import '../../css/u/uhvpqyzxp.css';
import '../../css/s/s-zhlbbmg.css';
import '../../css/a/at8xfhyjc.css';
import '../../css/x/x_y_7lbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m7_vfacpm"/><path class="uhvpqyzxp wm-k"/><path class="s-zhlbbmg wm-a"/><path class="at8xfhyjc wm-k"/><path class="wm-a x_y_7lbhg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:map-pin-check-sketch" {...props}></Icon>
