<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmf4_8bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fmf4_8bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:camera-video" {...props}></Icon>
