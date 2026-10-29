<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ib0-f2njr.css';
import '../../css/b/bh193db1h.css';
import '../../css/q/qayjij97x.css';
import '../../css/o/ocuzjvylb.css';
import '../../css/j/ja1wzrbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ib0-f2njr"/><path class="bh193db1h wm-k"/><path class="qayjij97x wm-s"/><path class="ocuzjvylb wm-k"/><path class="ja1wzrbcy wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-pull-request-closed-sketch" {...props}></Icon>
