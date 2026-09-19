<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al122vbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al122vbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:camera-video-light" {...props}></Icon>
