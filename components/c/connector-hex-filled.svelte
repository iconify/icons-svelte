<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebz0dxbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ebz0dxbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connector-hex-filled" {...props}></Icon>
