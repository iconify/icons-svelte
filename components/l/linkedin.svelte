<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vquvhkr6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vquvhkr6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:linkedin" {...props}></Icon>
