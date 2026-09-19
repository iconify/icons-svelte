<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgz0iz72w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="mgz0iz72w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:car-alt" {...props}></Icon>
