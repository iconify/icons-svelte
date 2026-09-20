<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yns8t4bbk.css';
import '../../css/d/djt0e9b0f.css';
import '../../css/o/oip2tteqt.css';
import '../../css/c/czuzz3bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yns8t4bbk"/><path clip-rule="evenodd" class="djt0e9b0f"/><path class="oip2tteqt"/><path class="czuzz3bda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-lib2-duotone" {...props}></Icon>
