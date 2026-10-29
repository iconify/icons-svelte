<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hbzcs2ysw.css';
import '../../css/a/a4la02b0t.css';
import '../../css/d/dk_c-sb7y.css';
import '../../css/h/hzbldnbux.css';
import '../../css/v/vjpnyegoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hbzcs2ysw wm-k"/><path class="a4la02b0t wm-shadow"/><path class="dk_c-sb7y wm-k"/><path class="hzbldnbux wm-a"/><path class="vjpnyegoq wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:poinsettia-engrave" {...props}></Icon>
