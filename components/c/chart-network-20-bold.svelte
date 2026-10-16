<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd6_1xb5y.css';
import '../../css/x/xo32v0bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dd6_1xb5y"/><path class="xo32v0bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-network-20-bold" {...props}></Icon>
