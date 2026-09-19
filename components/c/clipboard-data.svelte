<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u2nx3ko5q.css';
import '../../css/x/xczt9mbbm.css';
import '../../css/q/qzm-2f19d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="u2nx3ko5q"/><path class="xczt9mbbm"/><path class="qzm-2f19d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:clipboard-data" {...props}></Icon>
