<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugm2z76fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ugm2z76fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:duble-corner-arrow-4" {...props}></Icon>
