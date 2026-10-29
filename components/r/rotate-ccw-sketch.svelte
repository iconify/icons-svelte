<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/ql00m0bei.css';
import '../../css/y/ynleeubfu.css';
import '../../css/y/yitceubep.css';
import '../../css/f/fzyhonqct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ql00m0bei wm-k"/><path class="wm-a ynleeubfu"/><path class="wm-k yitceubep"/><path class="fzyhonqct wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rotate-ccw-sketch" {...props}></Icon>
