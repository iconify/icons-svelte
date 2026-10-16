<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rivd4q8kk.css';
import '../../css/l/ltjv97o_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rivd4q8kk"/><path class="ltjv97o_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:floor-plan-48" {...props}></Icon>
