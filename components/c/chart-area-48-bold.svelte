<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8ue7ubrb.css';
import '../../css/x/x-vy4em_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l8ue7ubrb"/><path class="x-vy4em_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-area-48-bold" {...props}></Icon>
