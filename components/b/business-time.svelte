<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r595-ubef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="r595-ubef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:business-time" {...props}></Icon>
