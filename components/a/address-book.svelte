<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pdsagcb-l.css';
import '../../css/x/xvqlmwgpz.css';
import '../../css/z/zmwvwabol.css';
import '../../css/l/luruawbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pdsagcb-l"/><path clip-rule="evenodd" class="xvqlmwgpz"/><path clip-rule="evenodd" class="zmwvwabol"/><path class="luruawbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:address-book" {...props}></Icon>
