<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ake5n5_8t.css';
import '../../css/r/r3en5bcjk.css';
import '../../css/s/s12z34bfj.css';
import '../../css/l/lekundbqi.css';
import '../../css/q/qln9-wiwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ake5n5_8t"/><path class="r3en5bcjk wm-k"/><path class="s12z34bfj wm-a"/><path class="lekundbqi wm-k"/><path class="qln9-wiwc wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:helicopter-sketch" {...props}></Icon>
