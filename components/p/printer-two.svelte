<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/l/l6qnrtb2h.css';
import '../../css/o/o39sc1brf.css';
import '../../css/f/fuxnvvbtt.css';
import '../../css/d/ddq83ybsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="l6qnrtb2h"/><rect class="o39sc1brf"/><path class="fuxnvvbtt"/><path class="ddq83ybsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:printer-two" {...props}></Icon>
