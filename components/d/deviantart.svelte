<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3-61p3_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3-61p3_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:deviantart" {...props}></Icon>
