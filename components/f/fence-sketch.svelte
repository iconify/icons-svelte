<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hwoxvnb5h.css';
import '../../css/z/zy6vbkbxh.css';
import '../../css/v/v8u8mm4xm.css';
import '../../css/q/qn79s9bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hwoxvnb5h wm-k"/><path class="wm-a zy6vbkbxh"/><path class="v8u8mm4xm wm-k"/><path class="qn79s9bck wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:fence-sketch" {...props}></Icon>
