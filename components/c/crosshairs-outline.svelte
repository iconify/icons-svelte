<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n574zphyq.css';
import '../../css/j/jx9kr4pbx.css';
import '../../css/t/tvvi5wtmo.css';
import '../../css/n/nzcm26aio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n574zphyq"/><path class="jx9kr4pbx"/><path class="tvvi5wtmo"/><path class="nzcm26aio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:crosshairs-outline" {...props}></Icon>
