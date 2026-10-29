<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9ttlvb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9ttlvb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-video-solid" {...props}></Icon>
