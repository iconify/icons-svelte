<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vm9wui7_h.css';
import '../../css/t/t5_glnobk.css';
import '../../css/c/c-0urdbth.css';
import '../../css/p/pausm5bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vm9wui7_h"/><path class="t5_glnobk wm-a"/><path class="c-0urdbth wm-k"/><path class="pausm5bgw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lock-sketch" {...props}></Icon>
