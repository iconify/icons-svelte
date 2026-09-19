<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g-d_bnj-u.css';
import '../../css/p/pf9f3hnhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="g-d_bnj-u"/><path clip-rule="evenodd" class="pf9f3hnhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:height2x-outline" {...props}></Icon>
