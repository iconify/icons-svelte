<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/vptemybwm.css';
import '../../css/l/l5t4kvb6g.css';
import '../../css/u/ucje65n3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="vptemybwm"/><path class="l5t4kvb6g"/><path class="ucje65n3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:clipboard-clock" {...props}></Icon>
