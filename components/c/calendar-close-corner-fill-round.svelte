<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd2zb8b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd2zb8b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-close-corner-fill-round" {...props}></Icon>
