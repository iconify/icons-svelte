<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rah527wei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rah527wei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:opened-folder" {...props}></Icon>
