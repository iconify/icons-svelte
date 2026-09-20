<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt5x5sxcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt5x5sxcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-circle-ai-line" {...props}></Icon>
