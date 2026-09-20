<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6d5tp4hc.css';
import '../../css/a/aji04yosq.css';
import '../../css/w/wmxx11b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6d5tp4hc"/><path class="aji04yosq"/><path class="wmxx11b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:animation-filled" {...props}></Icon>
