<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd3xn7bgt.css';
import '../../css/y/yj19_b3-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xd3xn7bgt"/><path class="yj19_b3-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-battery-20-bold" {...props}></Icon>
