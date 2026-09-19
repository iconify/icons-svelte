<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i56ns5bes.css';
import '../../css/o/ol-ghh4bp.css';
import '../../css/j/j2f-64b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="i56ns5bes"/><path clip-rule="evenodd" class="ol-ghh4bp"/><path class="j2f-64b_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:asthma-outline" {...props}></Icon>
