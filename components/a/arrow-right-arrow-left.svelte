<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwl9mh0ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bwl9mh0ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-right-arrow-left" {...props}></Icon>
