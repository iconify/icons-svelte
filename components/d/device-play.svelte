<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0elxrbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u0elxrbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:device-play" {...props}></Icon>
