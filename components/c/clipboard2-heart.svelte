<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/py_3t3bpr.css';
import '../../css/e/engdqdvya.css';
import '../../css/b/bwf1di5xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="py_3t3bpr"/><path class="engdqdvya"/><path class="bwf1di5xo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:clipboard2-heart" {...props}></Icon>
