<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n5crp9bgp.css';
import '../../css/l/lgultwbwl.css';
import '../../css/b/b2ekdbbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n5crp9bgp wm-a"/><path class="lgultwbwl wm-k"/><path class="b2ekdbbqw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:face-mask-sketch" {...props}></Icon>
