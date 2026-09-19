<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/falrj6b-v.css';
import '../../css/m/m7fafxb8d.css';
import '../../css/d/dxfu67mcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="falrj6b-v"/><path class="m7fafxb8d"/><path clip-rule="evenodd" class="dxfu67mcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chills" {...props}></Icon>
