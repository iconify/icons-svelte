<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e8f_t6izd.css';
import '../../css/p/pvd6u4yzv.css';
import '../../css/b/b2_d91zpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="e8f_t6izd"/><path class="pvd6u4yzv"/><path clip-rule="evenodd" class="b2_d91zpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:eye" {...props}></Icon>
