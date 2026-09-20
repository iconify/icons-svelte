<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/s/ss9mow7ak.css';
import '../../css/t/tn2sh5bsg.css';
import '../../css/x/xd6cdabmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="ss9mow7ak"/><path class="tn2sh5bsg"/><path class="xd6cdabmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:music-disable" {...props}></Icon>
