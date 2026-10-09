<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxvnz_b5x.css';
import '../../css/w/wieobab6h.css';
import '../../css/q/q24djubzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uxvnz_b5x"/><path class="wieobab6h"/><path class="q24djubzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-battery-48-bold" {...props}></Icon>
