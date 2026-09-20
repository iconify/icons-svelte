<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e75gkwkok.css';
import '../../css/z/z-uv8i-bl.css';
import '../../css/y/y23yr8bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e75gkwkok"/><path clip-rule="evenodd" class="z-uv8i-bl"/><path class="y23yr8bll"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:confetti2" {...props}></Icon>
