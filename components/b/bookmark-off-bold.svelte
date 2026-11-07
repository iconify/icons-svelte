<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcsgx-puk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcsgx-puk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-off-bold" {...props}></Icon>
