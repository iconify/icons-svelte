<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng84t3-ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ng84t3-ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:add-playlist" {...props}></Icon>
