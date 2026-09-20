<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0bn-3b4l.css';
import '../../css/v/vbnb4dskg.css';
import '../../css/t/t297pwbyd.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/t/tbjbnw6jh.css';
import '../../css/f/fotxbu58s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="l0bn-3b4l"><path class="vbnb4dskg"/><path class="t297pwbyd"/></g><g class="ij2x_72vy"><path class="tbjbnw6jh"/><path class="fotxbu58s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:dove" {...props}></Icon>
