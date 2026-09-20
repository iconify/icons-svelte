<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro7zm-t0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ro7zm-t0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waning-gibbous-5" {...props}></Icon>
