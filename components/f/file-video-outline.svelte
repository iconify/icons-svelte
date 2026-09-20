<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgfo8_bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgfo8_bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-video-outline" {...props}></Icon>
