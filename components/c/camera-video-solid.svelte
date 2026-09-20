<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqqbegx6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aqqbegx6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:camera-video-solid" {...props}></Icon>
