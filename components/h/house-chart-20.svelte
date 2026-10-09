<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7juawdew.css';
import '../../css/x/x_jd0jbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p7juawdew"/><path class="x_jd0jbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-chart-20" {...props}></Icon>
