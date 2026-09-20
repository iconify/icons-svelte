<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqhdsrbpo.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/b/b2tl1fbgr.css';
import '../../css/o/oi3x71bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fqhdsrbpo"/><g class="ij2x_72vy"><path class="b2tl1fbgr"/><path class="oi3x71bay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:archive" {...props}></Icon>
