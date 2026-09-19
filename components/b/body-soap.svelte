<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qf26nbclk.css';
import '../../css/o/ojxizkvjf.css';
import '../../css/g/gr2myqbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qf26nbclk"/><path class="ojxizkvjf"/><path class="gr2myqbwh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:body-soap" {...props}></Icon>
