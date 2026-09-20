<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw19l9bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw19l9bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:frame-check" {...props}></Icon>
