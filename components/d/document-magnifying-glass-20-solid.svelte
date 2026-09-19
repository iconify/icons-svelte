<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x1x_shbfr.css';
import '../../css/h/hrclzsfpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="x1x_shbfr"/><path clip-rule="evenodd" class="hrclzsfpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-magnifying-glass-20-solid" {...props}></Icon>
