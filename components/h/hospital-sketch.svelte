<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qzg7_0n5n.css';
import '../../css/e/e-03izbfa.css';
import '../../css/q/q9ldof2um.css';
import '../../css/n/nnnwjibgk.css';
import '../../css/m/mqvh0tbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qzg7_0n5n"/><path class="e-03izbfa wm-k"/><path class="q9ldof2um wm-a"/><path class="nnnwjibgk wm-k"/><path class="mqvh0tbrc wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hospital-sketch" {...props}></Icon>
