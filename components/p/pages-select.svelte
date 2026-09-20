<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2on7bc1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k2on7bc1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:pages-select" {...props}></Icon>
