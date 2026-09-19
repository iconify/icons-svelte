<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kpbhd5njz.css';
import '../../css/r/r4xt-4bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kpbhd5njz"/><path class="r4xt-4bjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:envelope-open-solid" {...props}></Icon>
