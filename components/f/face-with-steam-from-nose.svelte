<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7hlmrp-q.css';
import '../../css/c/cqxljhbfa.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/e/exzaj7nbx.css';
import '../../css/k/khwlr1_iy.css';
import '../../css/p/pp-gwnbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="g7hlmrp-q"/><path class="cqxljhbfa"/><g class="jn8qy4bru"><path class="exzaj7nbx"/><path class="khwlr1_iy"/><path class="pp-gwnbrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:face-with-steam-from-nose" {...props}></Icon>
