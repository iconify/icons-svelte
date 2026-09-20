<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4yt86kns.css';
import '../../css/f/fayfq0oyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path class="i4yt86kns"/><path class="fayfq0oyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domain-watchdog-dark" {...props}></Icon>
