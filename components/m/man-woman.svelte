<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sux_9dg_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sux_9dg_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:man-woman" {...props}></Icon>
