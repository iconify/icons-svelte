<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zcnvx6b2i.css';
import '../../css/l/lc2bhi9-j.css';
import '../../css/r/rfdykoh2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zcnvx6b2i"/><path clip-rule="evenodd" class="lc2bhi9-j"/><path class="rfdykoh2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:death-outline-24px" {...props}></Icon>
