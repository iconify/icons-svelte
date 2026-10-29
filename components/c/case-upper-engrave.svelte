<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w3vjh-tiq.css';
import '../../css/h/h6g7niile.css';
import '../../css/x/xfda1sb-y.css';
import '../../css/m/mcp_pbb2e.css';
import '../../css/o/ou82ezbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w3vjh-tiq wm-k"/><path class="h6g7niile wm-a"/><path class="wm-shadow xfda1sb-y"/><path class="mcp_pbb2e wm-k"/><path class="ou82ezbwj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:case-upper-engrave" {...props}></Icon>
