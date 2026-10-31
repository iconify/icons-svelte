<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpw3o1bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpw3o1bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:microphone-off-round" {...props}></Icon>
