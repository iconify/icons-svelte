<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv2g9obeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rv2g9obeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:exclamation-outline" {...props}></Icon>
