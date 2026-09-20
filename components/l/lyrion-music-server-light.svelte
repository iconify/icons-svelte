<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr08qbjbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qr08qbjbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lyrion-music-server-light" {...props}></Icon>
