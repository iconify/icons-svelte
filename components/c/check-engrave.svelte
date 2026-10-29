<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w2t9kvrcl.css';
import '../../css/e/e5drqabmo.css';
import '../../css/e/eerhch8on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w2t9kvrcl"/><path class="e5drqabmo wm-shadow"/><path class="eerhch8on"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:check-engrave" {...props}></Icon>
