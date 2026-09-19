<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x161jlf-f.css';
import '../../css/g/g7777bb0y.css';
import '../../css/z/z8cuebffl.css';
import '../../css/x/x-me61blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="x161jlf-f"/><path clip-rule="evenodd" class="g7777bb0y"/><path class="z8cuebffl"/><path clip-rule="evenodd" class="x-me61blo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cancerous-cell-nuclei" {...props}></Icon>
