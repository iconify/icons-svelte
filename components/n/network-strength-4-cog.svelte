<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9bo6tbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9bo6tbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:network-strength-4-cog" {...props}></Icon>
