<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs2wmdbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="cs2wmdbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-walking-arrow-loop-left" {...props}></Icon>
