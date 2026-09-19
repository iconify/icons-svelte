<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcrs9-qzk.css';
import '../../css/r/rtwbx3bhp.css';
import '../../css/s/so8rb_4ei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fcrs9-qzk"/><path class="rtwbx3bhp"/><path class="so8rb_4ei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-launchpad-s4" {...props}></Icon>
