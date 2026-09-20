<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd03i40nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd03i40nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:moon-stars" {...props}></Icon>
