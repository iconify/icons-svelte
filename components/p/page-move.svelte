<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-dc168xj.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/n/ne6g2tklt.css';
import '../../css/h/hv1f-5bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="l-dc168xj"/><g class="ij2x_72vy"><path class="ne6g2tklt"/><path class="hv1f-5bwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:page-move" {...props}></Icon>
