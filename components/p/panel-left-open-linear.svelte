<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xrry15w0o.css';
import '../../css/y/yc1eq-awn.css';
import '../../css/w/wk0dhccfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xrry15w0o"/><path class="yc1eq-awn"/><path class="wk0dhccfa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-left-open-linear" {...props}></Icon>
