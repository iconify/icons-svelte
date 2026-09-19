<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/plj3cxbsw.css';
import '../../css/w/wg6qfxr2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="plj3cxbsw"/><path clip-rule="evenodd" class="wg6qfxr2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:magnifying-glass-circle-16-solid" {...props}></Icon>
