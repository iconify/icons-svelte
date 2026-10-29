<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u1wanmiwb.css';
import '../../css/w/wr7_9j2ie.css';
import '../../css/g/g7nk-s9us.css';
import '../../css/o/ojvzaxljq.css';
import '../../css/p/p-xrl3bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u1wanmiwb"/><path class="wm-k wr7_9j2ie"/><path class="g7nk-s9us wm-a"/><path class="ojvzaxljq wm-k"/><path class="p-xrl3bvq wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle-plus-sketch" {...props}></Icon>
