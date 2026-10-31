<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vhrzp3m4f.css';
import '../../css/n/nakj5ubjo.css';
import '../../css/y/yriqevbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="vhrzp3m4f"/><path clip-rule="evenodd" class="nakj5ubjo"/><path clip-rule="evenodd" class="yriqevbyr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:egg-cell" {...props}></Icon>
