<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/asw3j7bnj.css';
import '../../css/k/k1u3rdh2l.css';
import '../../css/w/wwnf4bcjk.css';
import '../../css/w/wa93a239p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="asw3j7bnj"/><path class="k1u3rdh2l"/><path class="wwnf4bcjk"/><path class="wa93a239p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-1-outline" {...props}></Icon>
