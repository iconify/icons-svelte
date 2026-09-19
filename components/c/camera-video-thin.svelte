<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi1628bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi1628bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:camera-video-thin" {...props}></Icon>
