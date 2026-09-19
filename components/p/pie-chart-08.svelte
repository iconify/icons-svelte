<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/q/q1m15dbht.css';
import '../../css/h/hh5vpobvk.css';
import '../../css/l/l42-reayn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="shu3xdl9q"/><circle class="q1m15dbht"/><path class="hh5vpobvk"/><path class="l42-reayn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pie-chart-08" {...props}></Icon>
