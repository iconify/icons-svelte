<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fme87mb9p.css';
import '../../css/t/tjj8vhbjm.css';
import '../../css/v/vli0febuy.css';
import '../../css/x/xkx9-_bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="fme87mb9p"/><path clip-rule="evenodd" class="tjj8vhbjm"/><path class="vli0febuy"/><path class="xkx9-_bcv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:2g-outline" {...props}></Icon>
