<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8vxzdj-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8vxzdj-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-video-line" {...props}></Icon>
