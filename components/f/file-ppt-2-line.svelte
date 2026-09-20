<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz38d-r1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz38d-r1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-ppt-2-line" {...props}></Icon>
