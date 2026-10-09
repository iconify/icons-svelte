<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0oa-qzdz.css';
import '../../css/x/xv8x0vy4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="xv8x0vy4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pause-circle-20-bold" {...props}></Icon>
