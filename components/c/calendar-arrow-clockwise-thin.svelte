<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_whneb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x_whneb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-arrow-clockwise-thin" {...props}></Icon>
