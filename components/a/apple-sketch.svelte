<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nobnx9o2t.css';
import '../../css/p/p_bg0sbcz.css';
import '../../css/c/ckv6b3snt.css';
import '../../css/r/rhnvyuptx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nobnx9o2t"/><path class="p_bg0sbcz wm-a"/><path class="ckv6b3snt wm-k"/><path class="rhnvyuptx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:apple-sketch" {...props}></Icon>
