<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dp04q_i-b.css';
import '../../css/a/atb3k23ro.css';
import '../../css/f/fwuicyddt.css';
import '../../css/u/u-tk08bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dp04q_i-b"/><path class="atb3k23ro wm-a"/><path class="fwuicyddt wm-k"/><path class="u-tk08bep wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:choco-strawberry-sketch" {...props}></Icon>
