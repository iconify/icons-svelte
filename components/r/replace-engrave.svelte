<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/buvdbfbht.css';
import '../../css/u/ul5n8zbqi.css';
import '../../css/p/pou7dl5dq.css';
import '../../css/y/yt8-h8bsb.css';
import '../../css/c/cjj81ggta.css';
import '../../css/f/fl9qasb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="buvdbfbht wm-k"/><path class="ul5n8zbqi wm-a"/><path class="pou7dl5dq wm-shadow"/><path class="wm-k yt8-h8bsb"/><path class="cjj81ggta wm-a"/><path class="fl9qasb6v wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:replace-engrave" {...props}></Icon>
