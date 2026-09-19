<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/es4g5_fvh.css';
import '../../css/f/f89z5_a7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="es4g5_fvh"/><path clip-rule="evenodd" class="f89z5_a7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:allergies-outline-24px" {...props}></Icon>
