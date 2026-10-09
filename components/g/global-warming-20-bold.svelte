<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0uvzabfw.css';
import '../../css/y/y5duq9b8q.css';
import '../../css/r/rtl9t5b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y0uvzabfw"/><path class="y5duq9b8q"/><path class="rtl9t5b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:global-warming-20-bold" {...props}></Icon>
