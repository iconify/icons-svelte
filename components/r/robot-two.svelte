<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/v/vp82i6bmg.css';
import '../../css/w/wbev7pbna.css';
import '../../css/a/amfmd727l.css';
import '../../css/f/fkv52firo.css';
import '../../css/e/eia4hzbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="vp82i6bmg"/><path class="wbev7pbna"/><circle class="amfmd727l"/><path class="fkv52firo"/><path class="eia4hzbco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:robot-two" {...props}></Icon>
