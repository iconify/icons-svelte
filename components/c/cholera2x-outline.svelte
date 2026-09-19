<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d5uxspbsz.css';
import '../../css/d/d-wxtvbko.css';
import '../../css/u/u08m17z2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="d5uxspbsz"/><path class="d-wxtvbko"/><path clip-rule="evenodd" class="u08m17z2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cholera2x-outline" {...props}></Icon>
