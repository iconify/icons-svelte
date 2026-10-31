<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl-g2gbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl-g2gbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fullscreen-duotone-round" {...props}></Icon>
