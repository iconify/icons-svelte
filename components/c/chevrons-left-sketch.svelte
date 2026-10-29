<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sdhsa1lja.css';
import '../../css/a/aq94_1bal.css';
import '../../css/n/nh9e63xmb.css';
import '../../css/m/m3cpnbcue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sdhsa1lja wm-k"/><path class="aq94_1bal wm-a"/><path class="nh9e63xmb wm-k"/><path class="m3cpnbcue wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevrons-left-sketch" {...props}></Icon>
