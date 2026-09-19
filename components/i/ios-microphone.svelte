<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm6g_lhrv.css';
import '../../css/d/dgu1br39e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nm6g_lhrv"/><path class="dgu1br39e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-microphone" {...props}></Icon>
