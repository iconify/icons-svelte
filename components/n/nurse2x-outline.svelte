<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ow2ql5bqu.css';
import '../../css/d/d250fdbcq.css';
import '../../css/o/onl5habgw.css';
import '../../css/n/nhmm4pbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ow2ql5bqu"/><path clip-rule="evenodd" class="d250fdbcq"/><path class="onl5habgw"/><path clip-rule="evenodd" class="nhmm4pbny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:nurse2x-outline" {...props}></Icon>
