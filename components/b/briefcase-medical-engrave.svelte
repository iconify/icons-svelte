<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oi98yqb2d.css';
import '../../css/e/em9082e6z.css';
import '../../css/o/ozp63ob-s.css';
import '../../css/y/y3j3vjb4e.css';
import '../../css/h/hayg57blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oi98yqb2d wm-k"/><path class="em9082e6z wm-a"/><path class="ozp63ob-s wm-shadow"/><path class="wm-k y3j3vjb4e"/><path class="hayg57blh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:briefcase-medical-engrave" {...props}></Icon>
