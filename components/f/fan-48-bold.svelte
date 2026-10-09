<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl4xncchh.css';
import '../../css/q/qbfpednqz.css';
import '../../css/q/qewmfcczo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rl4xncchh"/><path class="qbfpednqz"/><path class="qewmfcczo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fan-48-bold" {...props}></Icon>
