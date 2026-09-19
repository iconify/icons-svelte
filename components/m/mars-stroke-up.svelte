<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5fy5w_1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="j5fy5w_1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mars-stroke-up" {...props}></Icon>
