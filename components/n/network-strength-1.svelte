<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc3cuxbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc3cuxbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:network-strength-1" {...props}></Icon>
