<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/la8juur7d.css';
import '../../css/l/lhvh71b1a.css';
import '../../css/u/ux0kji9-q.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="la8juur7d"/><path clip-rule="evenodd" class="lhvh71b1a"/><path class="ux0kji9-q"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:map-circle" {...props}></Icon>
