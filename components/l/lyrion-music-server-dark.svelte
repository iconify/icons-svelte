<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyzvr-brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vyzvr-brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lyrion-music-server-dark" {...props}></Icon>
