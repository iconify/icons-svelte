<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y4zp7bcdh.css';
import '../../css/r/r81hjcv_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="y4zp7bcdh"/><path clip-rule="evenodd" class="r81hjcv_h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:magnifying-glass-plus-20-solid" {...props}></Icon>
