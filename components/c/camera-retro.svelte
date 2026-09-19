<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs75febyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bs75febyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:camera-retro" {...props}></Icon>
