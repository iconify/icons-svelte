<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpel3hezc.css';
import '../../css/m/mu6uv0kwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tpel3hezc"/><path class="mu6uv0kwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-duration-curve-48-bold" {...props}></Icon>
