<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e31hwlboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e31hwlboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-up" {...props}></Icon>
