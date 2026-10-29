<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/y3rlqzmys.css';
import '../../css/i/i378c-rig.css';
import '../../css/r/rqaq9tbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="y3rlqzmys"/><path class="i378c-rig wm-a"/><path class="rqaq9tbyz wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-clock-solid" {...props}></Icon>
