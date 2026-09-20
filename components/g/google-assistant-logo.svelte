<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0y6x2b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0y6x2b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:google-assistant-logo" {...props}></Icon>
