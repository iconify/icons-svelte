<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixase-blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixase-blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:queue-music-outline" {...props}></Icon>
