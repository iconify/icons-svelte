<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa51hjvui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aa51hjvui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:calendar-stroke-16" {...props}></Icon>
