<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lstl2ybmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="lstl2ybmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mars-stroke-h" {...props}></Icon>
