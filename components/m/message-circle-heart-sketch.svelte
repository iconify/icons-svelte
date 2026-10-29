<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/usvo9t7dp.css';
import '../../css/g/gdq37xqqe.css';
import '../../css/f/fgjr8qb3s.css';
import '../../css/i/i0-mcjp7u.css';
import '../../css/x/xwf4h3f-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="usvo9t7dp"/><path class="gdq37xqqe wm-k"/><path class="fgjr8qb3s wm-a"/><path class="i0-mcjp7u wm-k"/><path class="wm-a xwf4h3f-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle-heart-sketch" {...props}></Icon>
