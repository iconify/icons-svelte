<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h8xub9bvx.css';
import '../../css/u/u94jc6b_g.css';
import '../../css/a/a_y8s9b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h8xub9bvx"/><path class="u94jc6b_g wm-shadow"/><path class="a_y8s9b1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:audio-waveform-engrave" {...props}></Icon>
