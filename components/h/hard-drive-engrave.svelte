<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/plgmnm5bs.css';
import '../../css/r/rvadobhgc.css';
import '../../css/c/c-n-9gpof.css';
import '../../css/k/km9xt0bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="plgmnm5bs wm-k"/><path class="rvadobhgc wm-shadow"/><path class="c-n-9gpof wm-k"/><path class="km9xt0bvl wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hard-drive-engrave" {...props}></Icon>
