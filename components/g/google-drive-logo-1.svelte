<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqiytfyza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqiytfyza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-drive-logo-1" {...props}></Icon>
