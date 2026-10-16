<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crxzhebgb.css';
import '../../css/r/rpsqcp5fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="crxzhebgb"/><path class="rpsqcp5fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-pie-slice-48-bold" {...props}></Icon>
