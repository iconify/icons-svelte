<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmsr3kb1i.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/n/n2p5-ed3s.css';
import '../../css/m/mt5816bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fmsr3kb1i"/><g class="brzn_0bpr"><path class="n2p5-ed3s"/><path class="mt5816bop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:power-on-off-symbol" {...props}></Icon>
