<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/t/tuvu8wjin.css';
import '../../css/q/qbegytbhw.css';
import '../../css/o/opakkwbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="tuvu8wjin"/><circle class="qbegytbhw"/><path class="opakkwbyw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:percentage" {...props}></Icon>
