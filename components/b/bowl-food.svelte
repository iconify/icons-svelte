<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0m7m2btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j0m7m2btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bowl-food" {...props}></Icon>
