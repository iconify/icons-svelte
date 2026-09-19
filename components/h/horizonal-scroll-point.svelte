<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy3anfbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy3anfbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:horizonal-scroll-point" {...props}></Icon>
