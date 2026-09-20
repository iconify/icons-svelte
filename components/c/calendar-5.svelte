<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gskczikik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gskczikik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:calendar-5" {...props}></Icon>
