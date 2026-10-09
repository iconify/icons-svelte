<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeuljtb4o.css';
import '../../css/r/rh2_wobnx.css';
import '../../css/w/w6_7avbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zeuljtb4o"/><path class="rh2_wobnx"/><path class="w6_7avbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydraulic-cylinder-20" {...props}></Icon>
