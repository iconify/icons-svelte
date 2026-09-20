<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd4oy6b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gd4oy6b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:move-2" {...props}></Icon>
