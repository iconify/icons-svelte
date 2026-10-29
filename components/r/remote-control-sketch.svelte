<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e6gga2tnl.css';
import '../../css/l/lqaiclbym.css';
import '../../css/e/et01vibno.css';
import '../../css/a/ae3oqxhnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e6gga2tnl wm-s"/><path class="lqaiclbym wm-k"/><path class="et01vibno wm-a"/><path class="ae3oqxhnu wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:remote-control-sketch" {...props}></Icon>
