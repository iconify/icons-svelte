<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d_evy9pfn.css';
import '../../css/e/e0sqh9n-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="d_evy9pfn"/><path clip-rule="evenodd" class="e0sqh9n-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-alert-20-solid" {...props}></Icon>
