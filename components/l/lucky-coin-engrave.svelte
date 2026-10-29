<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wdbvkhbpy.css';
import '../../css/x/x7ag86bpt.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/c/c-a4_nb-a.css';
import '../../css/q/q4fjqwbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wdbvkhbpy wm-k"/><path class="wm-shadow x7ag86bpt"/><path class="wm-k yw4fz_b6b"/><path class="c-a4_nb-a wm-k"/><path class="q4fjqwbqj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lucky-coin-engrave" {...props}></Icon>
