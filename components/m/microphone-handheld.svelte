<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bbt1n2-ga.css';
import '../../css/d/dtgyfrb2h.css';
import '../../css/q/qe_94vbov.css';
import '../../css/r/rpts7tzjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="bbt1n2-ga"/><path class="dtgyfrb2h"/><path class="qe_94vbov"/><path class="rpts7tzjm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:microphone-handheld" {...props}></Icon>
