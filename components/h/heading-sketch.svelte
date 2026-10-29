<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rppywc_mp.css';
import '../../css/q/q272iccrr.css';
import '../../css/g/gjkr0gbmj.css';
import '../../css/j/jqsbxnbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rppywc_mp wm-k"/><path class="q272iccrr wm-a"/><path class="gjkr0gbmj wm-k"/><path class="jqsbxnbrn wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heading-sketch" {...props}></Icon>
