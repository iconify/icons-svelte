<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4edo9bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r4edo9bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:rev" {...props}></Icon>
