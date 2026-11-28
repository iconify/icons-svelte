<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn4o5mb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cn4o5mb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-arrow-clockwise-bold" {...props}></Icon>
