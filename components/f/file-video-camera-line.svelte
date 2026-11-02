<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxtz_pbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxtz_pbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-video-camera-line" {...props}></Icon>
