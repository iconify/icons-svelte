<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/otl40_bpg.css';
import '../../css/s/svpx09b4p.css';
import '../../css/m/mcfcap6wp.css';
import '../../css/x/x7y_i-f5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="otl40_bpg"/><path clip-rule="evenodd" class="svpx09b4p"/><path class="mcfcap6wp"/><path class="x7y_i-f5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:bluetooth" {...props}></Icon>
