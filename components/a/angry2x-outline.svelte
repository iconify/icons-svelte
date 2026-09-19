<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jd5gxhl_b.css';
import '../../css/r/r26yq4b_e.css';
import '../../css/s/siob3cbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jd5gxhl_b"/><path class="r26yq4b_e"/><path clip-rule="evenodd" class="siob3cbvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:angry2x-outline" {...props}></Icon>
