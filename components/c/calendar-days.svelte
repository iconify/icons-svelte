<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0_s5_kbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="n0_s5_kbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:calendar-days" {...props}></Icon>
