<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhp5-v54c.css';
import '../../css/k/ku-g4jbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zhp5-v54c"/><path class="ku-g4jbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-network-48-bold" {...props}></Icon>
