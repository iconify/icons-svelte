<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov64d2bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov64d2bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-video-line" {...props}></Icon>
