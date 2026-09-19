<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jverwsbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jverwsbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:camera-video-off" {...props}></Icon>
