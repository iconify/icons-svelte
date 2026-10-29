<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mcjvr8b5u.css';
import '../../css/q/ql2ohgbvi.css';
import '../../css/g/geku89n_n.css';
import '../../css/r/r8c3ad2kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mcjvr8b5u"/><path class="ql2ohgbvi wm-a"/><path class="geku89n_n wm-k"/><path class="r8c3ad2kx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plane-landing-sketch" {...props}></Icon>
