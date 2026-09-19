<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/oom210bsn.css';
import '../../css/m/m9kbinsgl.css';
import '../../css/y/yvmgt3rgc.css';
import '../../css/c/c148ybb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="oom210bsn"/><path class="m9kbinsgl"/><path class="yvmgt3rgc"/><path class="c148ybb0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lips-outline" {...props}></Icon>
