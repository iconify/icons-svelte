<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-22xbcav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-22xbcav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-sparkle-round" {...props}></Icon>
