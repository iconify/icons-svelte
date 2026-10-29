<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/o/o5zrywbgr.css';
import '../../css/w/wr92o1bsm.css';
import '../../css/q/qaf5-tble.css';
import '../../css/w/w0sebyb3m.css';
import '../../css/v/va6-6v82i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="o5zrywbgr wm-deco"/><path class="wm-deco wr92o1bsm"/><path class="qaf5-tble wm-k"/><path class="w0sebyb3m wm-a"/><path class="va6-6v82i wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-minus-blueprint" {...props}></Icon>
