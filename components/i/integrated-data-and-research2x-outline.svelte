<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t3c766b8e.css';
import '../../css/d/dmu7i8byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="t3c766b8e"/><path clip-rule="evenodd" class="dmu7i8byd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:integrated-data-and-research2x-outline" {...props}></Icon>
