<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg4na6bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg4na6bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-traffic-barrier" {...props}></Icon>
