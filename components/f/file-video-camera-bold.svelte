<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8q5j9dzg.css';
import '../../css/w/wm3j448rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t8q5j9dzg"/><path class="wm3j448rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-video-camera-bold" {...props}></Icon>
