<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/m/m9569c2lu.css';
import '../../css/h/hda2sac4w.css';
import '../../css/w/wd3fsdbjr.css';
import '../../css/d/ddpx3-70y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="pr52f_b5y"><rect class="m9569c2lu"/><rect class="hda2sac4w"/><rect class="wd3fsdbjr"/><rect class="ddpx3-70y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:box-layout-3-bold" {...props}></Icon>
