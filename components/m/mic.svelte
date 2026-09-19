<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b9gbdlbzx.css';
import '../../css/n/nccnyto5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":32};
const content = `<g class="cuyn6tgcc"><path class="b9gbdlbzx"/><path class="nccnyto5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:mic" {...props}></Icon>
