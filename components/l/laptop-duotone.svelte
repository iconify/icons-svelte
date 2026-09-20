<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m9e7oqb2b.css';
import '../../css/v/vn71wy-bl.css';
import '../../css/t/t0dlfk87e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m9e7oqb2b"/><path clip-rule="evenodd" class="vn71wy-bl"/><path class="t0dlfk87e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:laptop-duotone" {...props}></Icon>
