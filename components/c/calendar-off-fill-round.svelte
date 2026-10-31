<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpcdrvr-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpcdrvr-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-off-fill-round" {...props}></Icon>
