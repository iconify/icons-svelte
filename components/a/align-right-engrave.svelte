<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kcbgbfb1b.css';
import '../../css/o/opnejxbao.css';
import '../../css/t/toalvz3ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kcbgbfb1b"/><path class="opnejxbao wm-shadow"/><path class="toalvz3ue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:align-right-engrave" {...props}></Icon>
