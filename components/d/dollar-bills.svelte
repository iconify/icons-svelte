<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dlfsdvbll.css';
import '../../css/y/yuhc8jo4x.css';
import '../../css/x/xmr7rhb3p.css';
import '../../css/u/uo9rxdr_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="dlfsdvbll"/><path class="yuhc8jo4x"/><path clip-rule="evenodd" class="xmr7rhb3p"/><path class="uo9rxdr_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:dollar-bills" {...props}></Icon>
