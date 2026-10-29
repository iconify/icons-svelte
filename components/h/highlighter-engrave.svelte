<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zguq1dbdi.css';
import '../../css/a/aibqp5ysk.css';
import '../../css/a/a4ko41ypx.css';
import '../../css/j/jgr-ou_0r.css';
import '../../css/t/tvc6zw-sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k zguq1dbdi"/><path class="aibqp5ysk wm-a"/><path class="a4ko41ypx wm-shadow"/><path class="jgr-ou_0r wm-k"/><path class="tvc6zw-sb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:highlighter-engrave" {...props}></Icon>
