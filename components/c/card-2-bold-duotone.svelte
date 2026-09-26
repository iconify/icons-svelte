<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ad4x7oblk.css';
import '../../css/h/ha9e9bcnw.css';
import '../../css/j/j9na07rou.css';
import '../../css/m/m0a5tpbcr.css';
import '../../css/o/o1cpgsbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ad4x7oblk"/><path clip-rule="evenodd" class="ha9e9bcnw"/><path class="j9na07rou"/><path class="m0a5tpbcr"/><path class="o1cpgsbzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-2-bold-duotone" {...props}></Icon>
