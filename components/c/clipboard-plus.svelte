<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r8t79bctm.css';
import '../../css/x/xczt9mbbm.css';
import '../../css/q/qzm-2f19d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="r8t79bctm"/><path class="xczt9mbbm"/><path class="qzm-2f19d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:clipboard-plus" {...props}></Icon>
