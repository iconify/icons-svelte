<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v8z010bwq.css';
import '../../css/k/kpp0gibyb.css';
import '../../css/u/uxu_holod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path class="v8z010bwq"/><path class="kpp0gibyb"/><path clip-rule="evenodd" class="uxu_holod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:collapse-all-compact" {...props}></Icon>
