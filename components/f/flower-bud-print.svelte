<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dy34s966k.css';
import '../../css/d/dti_lwbpo.css';
import '../../css/r/rultu2b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dy34s966k"/><path class="dti_lwbpo"/><path clip-rule="evenodd" class="rultu2b4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:flower-bud-print" {...props}></Icon>
