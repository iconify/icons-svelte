<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/trm14bb_w.css';
import '../../css/f/fl3cbbb-h.css';
import '../../css/j/j7oq_bbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="trm14bb_w"/><path clip-rule="evenodd" class="fl3cbbb-h"/><path class="j7oq_bbrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:repo-fetch" {...props}></Icon>
