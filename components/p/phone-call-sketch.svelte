<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cn2v9_bei.css';
import '../../css/f/f1o7adbih.css';
import '../../css/y/y2ih3rbsr.css';
import '../../css/a/aqkf81bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cn2v9_bei"/><path class="f1o7adbih wm-s"/><path class="wm-k y2ih3rbsr"/><path class="aqkf81bgs wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:phone-call-sketch" {...props}></Icon>
