<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8yi72bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="q8yi72bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hourglass-half" {...props}></Icon>
