<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr__skb2i.css';
import '../../css/e/ek3d--bzq.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/w/w5srz5bvt.css';
import '../../css/n/ne0fmbx4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="vr__skb2i"/><path class="ek3d--bzq"/><g class="ij2x_72vy"><path class="w5srz5bvt"/><path class="ne0fmbx4f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:clamp" {...props}></Icon>
