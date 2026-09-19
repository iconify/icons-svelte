<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btx30rb9t.css';
import '../../css/a/adk1a1f8p.css';
import '../../css/y/yx977ubbo.css';
import '../../css/m/my4dskblt.css';
import '../../css/r/r_ykrfbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="btx30rb9t"><path class="adk1a1f8p"/><path class="yx977ubbo"/><path class="my4dskblt"/><path class="r_ykrfbmv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:kungfu" {...props}></Icon>
