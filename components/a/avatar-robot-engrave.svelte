<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qqb7o0b_l.css';
import '../../css/j/jz00m71ah.css';
import '../../css/w/w15tups4r.css';
import '../../css/u/umz1zqvzv.css';
import '../../css/g/gyq63ic-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qqb7o0b_l wm-k"/><path class="jz00m71ah wm-a"/><path class="w15tups4r wm-shadow"/><path class="umz1zqvzv wm-k"/><path class="gyq63ic-u wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-robot-engrave" {...props}></Icon>
