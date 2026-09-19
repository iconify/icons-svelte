<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sayb-0bmx.css';
import '../../css/i/ircx_pb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sayb-0bmx"/><path class="ircx_pb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:airplay-filled" {...props}></Icon>
