<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt2iqb_gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yt2iqb_gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:music-equalizer" {...props}></Icon>
