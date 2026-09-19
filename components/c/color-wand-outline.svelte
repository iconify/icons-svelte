<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/far_cdbom.css';
import '../../css/v/vmzs2cilw.css';
import '../../css/r/rfghtubvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect transform="rotate(-45 312.002 311.994)" class="far_cdbom"/><path class="vmzs2cilw"/><path class="rfghtubvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:color-wand-outline" {...props}></Icon>
