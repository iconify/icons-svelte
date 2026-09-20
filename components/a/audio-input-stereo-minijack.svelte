<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwk2ih8jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwk2ih8jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:audio-input-stereo-minijack" {...props}></Icon>
