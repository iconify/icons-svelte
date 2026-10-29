<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/aqikjdb1l.css';
import '../../css/j/jjtf8bcgi.css';
import '../../css/z/zyla41bsz.css';
import '../../css/h/hbi8hhkfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="aqikjdb1l wm-k"/><path class="jjtf8bcgi wm-shadow"/><path class="wm-k zyla41bsz"/><path class="hbi8hhkfx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flower-engrave" {...props}></Icon>
