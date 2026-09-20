<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkx84-bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkx84-bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:image-v" {...props}></Icon>
