<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hymmnccew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hymmnccew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:device-camera-video-16" {...props}></Icon>
