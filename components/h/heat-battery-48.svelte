<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pntg1acwg.css';
import '../../css/p/pu7nh0bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pntg1acwg"/><path class="pu7nh0bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-battery-48" {...props}></Icon>
