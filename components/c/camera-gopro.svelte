<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmfieubqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmfieubqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-gopro" {...props}></Icon>
