<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvkwf439u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dvkwf439u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:circle-arrow-right" {...props}></Icon>
