<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vifd6_bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vifd6_bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:calendar-1" {...props}></Icon>
