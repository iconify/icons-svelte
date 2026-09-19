<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5mv57n7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s5mv57n7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:playback-rate-1x" {...props}></Icon>
