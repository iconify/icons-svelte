<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-ux5kblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-ux5kblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:calendar-3" {...props}></Icon>
