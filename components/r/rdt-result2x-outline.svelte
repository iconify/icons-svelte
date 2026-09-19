<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r8f7u0bby.css';
import '../../css/t/t002y2qal.css';
import '../../css/s/sgaaagkzw.css';
import '../../css/v/vl_70lije.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="r8f7u0bby"/><path clip-rule="evenodd" class="t002y2qal"/><path clip-rule="evenodd" class="sgaaagkzw"/><path class="vl_70lije"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rdt-result2x-outline" {...props}></Icon>
