<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r87fz2wei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r87fz2wei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:o-brick" {...props}></Icon>
