<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm3vy_9vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zm3vy_9vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:funnel-16-solid" {...props}></Icon>
