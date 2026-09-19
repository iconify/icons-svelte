<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w9wpg9cgy.css';
import '../../css/x/xyvolmu6b.css';
import '../../css/n/nnw93lbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w9wpg9cgy"/><path class="xyvolmu6b"/><path clip-rule="evenodd" class="nnw93lbbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cane2x-outline" {...props}></Icon>
