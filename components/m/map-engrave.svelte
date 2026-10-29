<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q-tl41blh.css';
import '../../css/j/j56euqa_l.css';
import '../../css/h/hpnt--oey.css';
import '../../css/e/eoiz0rolg.css';
import '../../css/p/p2z9olxff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q-tl41blh wm-k"/><path class="j56euqa_l wm-a"/><path class="hpnt--oey wm-shadow"/><path class="eoiz0rolg wm-k"/><path class="p2z9olxff wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:map-engrave" {...props}></Icon>
