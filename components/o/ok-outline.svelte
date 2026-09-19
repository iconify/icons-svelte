<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hobtoeb-y.css';
import '../../css/i/i5jeaub5q.css';
import '../../css/s/siob3cbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="hobtoeb-y"/><path clip-rule="evenodd" class="i5jeaub5q"/><path clip-rule="evenodd" class="siob3cbvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ok-outline" {...props}></Icon>
