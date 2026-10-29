<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jrv87_b6w.css';
import '../../css/p/p3ugz7wqs.css';
import '../../css/b/b82dfnb_o.css';
import '../../css/i/i9rgmobgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jrv87_b6w wm-k"/><path class="p3ugz7wqs wm-shadow"/><path class="b82dfnb_o wm-k"/><path class="i9rgmobgb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:octagon-alert-engrave" {...props}></Icon>
