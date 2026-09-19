<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt0xhaboe.css';
import '../../css/d/d_rfajbtq.css';
import '../../css/y/yalo82bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rt0xhaboe"/><path class="d_rfajbtq"/><path class="yalo82bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackpushpin" {...props}></Icon>
