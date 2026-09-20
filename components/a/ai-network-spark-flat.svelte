<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r1k6ffbcm.css';
import '../../css/m/m9rcm8bne.css';
import '../../css/g/gzpo1u_la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r1k6ffbcm"/><path class="m9rcm8bne"/><path class="gzpo1u_la"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:ai-network-spark-flat" {...props}></Icon>
