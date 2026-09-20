<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2wjsd2bw.css';
import '../../css/b/br6g27b-g.css';
import '../../css/p/pnzorx2au.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/c/c4ybfgbdw.css';
import '../../css/n/nxjkb3bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="r2wjsd2bw"/><path class="br6g27b-g"/><path class="pnzorx2au"/><g class="jn8qy4bru"><path class="c4ybfgbdw"/><path class="nxjkb3bbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:loudspeaker" {...props}></Icon>
