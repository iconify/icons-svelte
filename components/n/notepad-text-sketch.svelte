<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fe-6m83ye.css';
import '../../css/g/gf4x890sv.css';
import '../../css/j/jyce257fr.css';
import '../../css/o/oia2u1l4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fe-6m83ye"/><path class="gf4x890sv wm-a"/><path class="jyce257fr wm-k"/><path class="oia2u1l4x wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:notepad-text-sketch" {...props}></Icon>
