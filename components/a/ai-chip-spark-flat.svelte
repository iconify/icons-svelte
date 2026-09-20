<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bwr_qmbzz.css';
import '../../css/x/xrg4jxbpo.css';
import '../../css/l/lger5s6qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bwr_qmbzz"/><path class="xrg4jxbpo"/><path class="lger5s6qw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:ai-chip-spark-flat" {...props}></Icon>
