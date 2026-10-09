<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oejyfcccr.css';
import '../../css/z/zv_mybbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oejyfcccr"/><path class="zv_mybbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-line-20-bold" {...props}></Icon>
