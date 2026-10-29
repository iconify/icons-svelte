<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b-jcbhbow.css';
import '../../css/o/oi09glzat.css';
import '../../css/s/saw55rb-m.css';
import '../../css/g/gfb62bt5g.css';
import '../../css/c/ck_6qidwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b-jcbhbow wm-k"/><path class="oi09glzat wm-a"/><path class="saw55rb-m wm-shadow"/><path class="gfb62bt5g wm-k"/><path class="ck_6qidwg wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:contact-engrave" {...props}></Icon>
