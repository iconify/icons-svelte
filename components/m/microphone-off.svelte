<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbv695bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vbv695bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:microphone-off" {...props}></Icon>
