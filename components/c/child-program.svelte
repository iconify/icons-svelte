<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zg2o2y4jg.css';
import '../../css/e/en2yxb8bj.css';
import '../../css/v/vy5ihzwxr.css';
import '../../css/c/ccw6g8mcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="zg2o2y4jg"/><path clip-rule="evenodd" class="en2yxb8bj"/><path class="vy5ihzwxr"/><path clip-rule="evenodd" class="ccw6g8mcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:child-program" {...props}></Icon>
