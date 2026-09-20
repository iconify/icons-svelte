<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d71j6bs8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21.065,"height":31.99,"left":0.005};
const content = `<path class="d71j6bs8z ingov-blue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:inprs" {...props}></Icon>
