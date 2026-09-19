<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t8e-pkcgt.css';
import '../../css/t/t6qagibeg.css';
import '../../css/x/xvj31lbcb.css';
import '../../css/p/p12apbc6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="t8e-pkcgt"/><path class="t6qagibeg"/><path class="xvj31lbcb"/><path class="p12apbc6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gas-stove" {...props}></Icon>
