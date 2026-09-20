<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7i0xybwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p7i0xybwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:device-play-filled" {...props}></Icon>
