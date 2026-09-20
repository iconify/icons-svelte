<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw90mob3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vw90mob3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-with-shekel" {...props}></Icon>
