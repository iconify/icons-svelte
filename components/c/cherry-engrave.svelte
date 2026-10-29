<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xihraibpt.css';
import '../../css/o/opiqdzbqt.css';
import '../../css/e/e4lfdh1cv.css';
import '../../css/v/vrm34f8gd.css';
import '../../css/o/ows2wwb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xihraibpt"/><path class="opiqdzbqt wm-a"/><path class="e4lfdh1cv wm-shadow"/><path class="vrm34f8gd wm-k"/><path class="ows2wwb4n wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cherry-engrave" {...props}></Icon>
