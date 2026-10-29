<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/unyxg6bnj.css';
import '../../css/o/o5gwckbir.css';
import '../../css/x/xknnqlb9b.css';
import '../../css/h/hi-3gxb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="unyxg6bnj wm-k"/><path class="o5gwckbir wm-s"/><path class="wm-k xknnqlb9b"/><path class="hi-3gxb_k wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-x-sketch" {...props}></Icon>
