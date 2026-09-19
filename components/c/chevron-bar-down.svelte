<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erays-b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="erays-b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-bar-down" {...props}></Icon>
