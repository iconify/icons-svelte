<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp9rkhbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp9rkhbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-zoom-out" {...props}></Icon>
