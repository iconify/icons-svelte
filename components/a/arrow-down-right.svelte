<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4o8gb03u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u4o8gb03u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-right" {...props}></Icon>
