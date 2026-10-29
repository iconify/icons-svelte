<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sui5t1bhg.css';
import '../../css/j/jalfqco1n.css';
import '../../css/a/aari1qi6v.css';
import '../../css/j/jmvv3kbnk.css';
import '../../css/h/hp_yrebrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sui5t1bhg wm-k"/><path class="jalfqco1n wm-a"/><path class="aari1qi6v wm-shadow"/><path class="jmvv3kbnk wm-k"/><path class="hp_yrebrn wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-x-engrave" {...props}></Icon>
