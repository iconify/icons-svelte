<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6iikjgcv.css';
import '../../css/m/m0wodmeth.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/b/b5h4wgblb.css';
import '../../css/y/yaxh6xbhq.css';
import '../../css/j/jfebrr_wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="s6iikjgcv"/><path class="m0wodmeth"/><g class="ij2x_72vy"><path class="b5h4wgblb"/><path class="yaxh6xbhq"/><path class="jfebrr_wi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:face-vomiting" {...props}></Icon>
