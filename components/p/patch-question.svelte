<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nybkspifn.css';
import '../../css/n/n1u32wbyg.css';
import '../../css/b/b6v88-svo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="nybkspifn"/><path class="n1u32wbyg"/><path class="b6v88-svo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:patch-question" {...props}></Icon>
