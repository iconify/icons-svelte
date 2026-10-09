<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktpu1oifd.css';
import '../../css/f/fo0_yzbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ktpu1oifd"/><path class="fo0_yzbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-data-20-bold" {...props}></Icon>
