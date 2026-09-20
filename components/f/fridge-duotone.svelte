<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u5bv9rbda.css';
import '../../css/p/pt1kf0bik.css';
import '../../css/c/cdt14qbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="u5bv9rbda"/><path class="pt1kf0bik"/><path class="cdt14qbmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fridge-duotone" {...props}></Icon>
