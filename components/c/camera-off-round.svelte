<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sszkzp2nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sszkzp2nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:camera-off-round" {...props}></Icon>
