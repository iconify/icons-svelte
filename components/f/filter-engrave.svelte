<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y51shub2s.css';
import '../../css/q/qxwv1nbma.css';
import '../../css/l/l5bot_fnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="y51shub2s"/><path class="qxwv1nbma wm-shadow"/><path class="l5bot_fnt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:filter-engrave" {...props}></Icon>
