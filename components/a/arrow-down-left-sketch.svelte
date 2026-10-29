<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u-eo-eb_s.css';
import '../../css/s/sov9jobbh.css';
import '../../css/b/bd3wwabse.css';
import '../../css/m/mugdapbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u-eo-eb_s wm-k"/><path class="sov9jobbh wm-a"/><path class="bd3wwabse wm-k"/><path class="mugdapbyt wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-down-left-sketch" {...props}></Icon>
