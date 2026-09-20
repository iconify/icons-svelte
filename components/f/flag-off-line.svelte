<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n047vkb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n047vkb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flag-off-line" {...props}></Icon>
