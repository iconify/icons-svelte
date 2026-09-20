<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at882_b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at882_b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bus-articulated-front" {...props}></Icon>
