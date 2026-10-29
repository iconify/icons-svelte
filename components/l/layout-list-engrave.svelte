<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d1883fb6h.css';
import '../../css/y/yniokbc4v.css';
import '../../css/p/p05jtukau.css';
import '../../css/t/t9g5kvbye.css';
import '../../css/t/trdla8jeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d1883fb6h wm-k"/><path class="wm-a yniokbc4v"/><path class="p05jtukau wm-shadow"/><path class="t9g5kvbye wm-k"/><path class="trdla8jeo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:layout-list-engrave" {...props}></Icon>
