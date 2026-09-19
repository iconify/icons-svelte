<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5q4pvb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":408};
const content = `<path class="c5q4pvb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:mic-off" {...props}></Icon>
