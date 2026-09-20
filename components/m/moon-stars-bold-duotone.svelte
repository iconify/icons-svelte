<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zjvhwgq2h.css';
import '../../css/h/h-w6sbb4t.css';
import '../../css/t/ton5smgkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zjvhwgq2h"/><path class="h-w6sbb4t"/><path class="ton5smgkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:moon-stars-bold-duotone" {...props}></Icon>
