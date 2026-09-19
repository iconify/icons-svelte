<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/x/xhkw50bnm.css';
import '../../css/a/aqxo_qbvg.css';
import '../../css/p/pmhy0ibjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="xhkw50bnm"/><path class="aqxo_qbvg"/><path class="pmhy0ibjl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heartbeat" {...props}></Icon>
