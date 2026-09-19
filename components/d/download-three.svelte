<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/u/utf5_xbzs.css';
import '../../css/v/v31u9obdf.css';
import '../../css/n/nv47c26na.css';
import '../../css/z/zyl4k9yjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="utf5_xbzs"/><path class="v31u9obdf"/><path class="nv47c26na"/><path class="zyl4k9yjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:download-three" {...props}></Icon>
