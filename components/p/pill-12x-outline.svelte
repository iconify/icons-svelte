<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cyzx-o7pi.css';
import '../../css/w/wi8hi9iwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="cyzx-o7pi"/><path clip-rule="evenodd" class="wi8hi9iwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pill-12x-outline" {...props}></Icon>
