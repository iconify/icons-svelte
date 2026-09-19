<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1x2ejc7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="r1x2ejc7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bus-simple" {...props}></Icon>
