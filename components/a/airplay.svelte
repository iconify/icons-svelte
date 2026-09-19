<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8p7xqizv.css';
import '../../css/i/ircx_pb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q8p7xqizv"/><path class="ircx_pb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:airplay" {...props}></Icon>
