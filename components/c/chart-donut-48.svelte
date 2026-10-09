<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpeu_j1mo.css';
import '../../css/c/cmhnqibcc.css';
import '../../css/w/wqsnrac2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tpeu_j1mo"/><path class="cmhnqibcc"/><path class="wqsnrac2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-donut-48" {...props}></Icon>
