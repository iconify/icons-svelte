<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fcuyecskv.css';
import '../../css/b/bqc8i0b_d.css';
import '../../css/z/znrnx5bpx.css';
import '../../css/i/i7y2ohbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="cuyn6tgcc"><path class="fcuyecskv"/><path class="bqc8i0b_d"/><path class="znrnx5bpx"/><path class="i7y2ohbei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:googlecloud" {...props}></Icon>
