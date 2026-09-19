<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n7cp5yjmv.css';
import '../../css/w/w1y7w7bpk.css';
import '../../css/u/ua6bxzbzs.css';
import '../../css/e/ek70m4tim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n7cp5yjmv"/><path class="w1y7w7bpk"/><path class="ua6bxzbzs"/><path class="ek70m4tim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:map-marker-1-outline" {...props}></Icon>
