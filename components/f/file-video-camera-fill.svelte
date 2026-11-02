<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg023cbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg023cbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-video-camera-fill" {...props}></Icon>
