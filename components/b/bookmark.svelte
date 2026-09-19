<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/q/qgryp0big.css';
import '../../css/e/eif875blk.css';
import '../../css/u/uuadrccgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="qgryp0big"/><path clip-rule="evenodd" class="eif875blk"/><path class="uuadrccgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bookmark" {...props}></Icon>
