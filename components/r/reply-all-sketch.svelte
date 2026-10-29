<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/op9vzzuvw.css';
import '../../css/v/vc60k4bry.css';
import '../../css/c/cus0ge-pw.css';
import '../../css/e/eew58wbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="op9vzzuvw wm-k"/><path class="vc60k4bry wm-a"/><path class="cus0ge-pw wm-k"/><path class="eew58wbvh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:reply-all-sketch" {...props}></Icon>
