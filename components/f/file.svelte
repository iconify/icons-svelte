<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zr_lbtkpu.css';
import '../../css/w/wx_97fbvz.css';
import '../../css/o/o-mxp99xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="zr_lbtkpu"/><path class="wx_97fbvz"/><path class="o-mxp99xh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:file" {...props}></Icon>
