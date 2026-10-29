<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/ti149fj5l.css';
import '../../css/x/xnqlj98sb.css';
import '../../css/r/rftpgmx8c.css';
import '../../css/l/lktwn-bjm.css';
import '../../css/i/ik22gveqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ti149fj5l wm-k"/><path class="wm-a xnqlj98sb"/><path class="rftpgmx8c wm-shadow"/><path class="lktwn-bjm wm-k"/><path class="ik22gveqy wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-output-engrave" {...props}></Icon>
