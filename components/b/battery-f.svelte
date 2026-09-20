<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oa8x24byn.css';
import '../../css/n/nlz_nebpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<g class="cuyn6tgcc"><path class="oa8x24byn"/><path class="nlz_nebpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:battery-f" {...props}></Icon>
