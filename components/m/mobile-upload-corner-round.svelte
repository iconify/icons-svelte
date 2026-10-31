<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu73ictjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu73ictjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mobile-upload-corner-round" {...props}></Icon>
