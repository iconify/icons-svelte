<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p4ylr4bzn.css';
import '../../css/f/fv6kukroi.css';
import '../../css/e/euj49csjz.css';
import '../../css/y/yd-bdcbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p4ylr4bzn wm-k"/><path class="fv6kukroi wm-shadow"/><path class="euj49csjz wm-k"/><path class="wm-a yd-bdcbtt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:captions-engrave" {...props}></Icon>
