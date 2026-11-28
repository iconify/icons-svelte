<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psxbs1bui.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4--ovbba.css';
import '../../css/e/e_r8k3b4h.css';
import '../../css/q/qad1b2bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psxbs1bui secondary"/><g class="dt0cm9dhy primary"><path class="l4--ovbba"/><path class="e_r8k3b4h"/><path class="qad1b2bwq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-bitcoin-duo" {...props}></Icon>
