<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sw3_qvbyu.css';
import '../../css/j/jfki3ygnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="sw3_qvbyu"/><path class="jfki3ygnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:copy" {...props}></Icon>
