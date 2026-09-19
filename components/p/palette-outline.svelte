<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xmrttlbyf.css';
import '../../css/t/tvb-a3rpz.css';
import '../../css/j/jabh3esin.css';
import '../../css/k/kb_nqjyfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xmrttlbyf"/><path class="tvb-a3rpz"/><path class="jabh3esin"/><path class="kb_nqjyfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:palette-outline" {...props}></Icon>
