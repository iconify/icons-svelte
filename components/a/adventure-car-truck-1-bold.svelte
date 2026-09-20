<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngl567b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngl567b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:adventure-car-truck-1-bold" {...props}></Icon>
