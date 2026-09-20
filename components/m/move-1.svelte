<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfan8ddsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sfan8ddsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:move-1" {...props}></Icon>
