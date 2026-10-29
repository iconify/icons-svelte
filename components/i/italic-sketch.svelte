<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l71k8fb0y.css';
import '../../css/e/eeuoneb2d.css';
import '../../css/i/i1fwsxj1m.css';
import '../../css/n/n54gpdb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l71k8fb0y wm-k"/><path class="eeuoneb2d wm-a"/><path class="i1fwsxj1m wm-k"/><path class="n54gpdb3n wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:italic-sketch" {...props}></Icon>
