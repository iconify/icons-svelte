<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0_4ajs8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r0_4ajs8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:duble-corner-arrow-6" {...props}></Icon>
