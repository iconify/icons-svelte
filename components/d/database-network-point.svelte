<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/alaw1vzcj.css';
import '../../css/x/xqmg7ycna.css';
import '../../css/i/ifmva9g2b.css';
import '../../css/w/wwk6gdwuk.css';
import '../../css/l/l72am6s0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="alaw1vzcj"/><path class="xqmg7ycna"/><path class="ifmva9g2b"/><path class="wwk6gdwuk"/><path class="l72am6s0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:database-network-point" {...props}></Icon>
