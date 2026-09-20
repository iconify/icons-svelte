<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cxsluibud.css';
import '../../css/m/mg3ip9u7s.css';
import '../../css/a/abc2udchl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cxsluibud"/><path class="mg3ip9u7s"/><path class="abc2udchl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:directions-sharp" {...props}></Icon>
