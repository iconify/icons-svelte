<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pevnz3bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pevnz3bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:part-of-circle-2" {...props}></Icon>
