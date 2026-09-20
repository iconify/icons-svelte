<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfchthbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zfchthbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-video-off" {...props}></Icon>
