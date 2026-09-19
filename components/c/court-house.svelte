<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qmo-mnbwk.css';
import '../../css/v/v920rdbob.css';
import '../../css/m/ms12apbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qmo-mnbwk"/><path class="v920rdbob"/><path class="ms12apbye"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:court-house" {...props}></Icon>
