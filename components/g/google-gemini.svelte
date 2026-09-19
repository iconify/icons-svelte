<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj-b23bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj-b23bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:google-gemini" {...props}></Icon>
