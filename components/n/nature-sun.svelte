<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_0r4ob-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c_0r4ob-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:nature-sun" {...props}></Icon>
