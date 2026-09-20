<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo9gusfap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo9gusfap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:badge-captions-sharp" {...props}></Icon>
