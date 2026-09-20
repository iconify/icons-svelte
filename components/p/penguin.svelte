<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b262p1bwm.css';
import '../../css/j/jubl0mbgj.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/b/bw835zz1c.css';
import '../../css/l/lyurstbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="b262p1bwm"/><path class="jubl0mbgj"/><g class="ij2x_72vy"><path class="bw835zz1c"/><path class="lyurstbcd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:penguin" {...props}></Icon>
