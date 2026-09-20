<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izhxi_b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izhxi_b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bookmark-3-fill" {...props}></Icon>
