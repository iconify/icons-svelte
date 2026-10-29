<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ac4w-4l8x.css';
import '../../css/c/crugkkdfe.css';
import '../../css/f/ffmjv2bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ac4w-4l8x"/><path class="crugkkdfe wm-k"/><path class="ffmjv2bzj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-koala-sketch" {...props}></Icon>
