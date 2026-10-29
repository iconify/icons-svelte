<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v--q92aev.css';
import '../../css/i/ir6haibsd.css';
import '../../css/g/gorsochjg.css';
import '../../css/q/qy6s686ad.css';
import '../../css/y/yatyg0v9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v--q92aev"/><path class="ir6haibsd wm-shadow"/><path class="gorsochjg"/><path class="qy6s686ad"/><path class="yatyg0v9y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-pull-request-engrave" {...props}></Icon>
