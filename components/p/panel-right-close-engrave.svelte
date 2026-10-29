<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/okex9absk.css';
import '../../css/m/mte5nkbne.css';
import '../../css/t/tlpgutb5x.css';
import '../../css/v/vwzncsbmf.css';
import '../../css/z/zub4acc2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="okex9absk wm-k"/><path class="mte5nkbne wm-a"/><path class="tlpgutb5x wm-shadow"/><path class="vwzncsbmf wm-k"/><path class="wm-a zub4acc2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-right-close-engrave" {...props}></Icon>
