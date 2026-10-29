<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gh8cru6va.css';
import '../../css/p/phhcb1buc.css';
import '../../css/x/xmz6v6vvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gh8cru6va"/><path class="phhcb1buc wm-k"/><path class="wm-a xmz6v6vvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:camera-sketch" {...props}></Icon>
