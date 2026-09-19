<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xn4aaqbkb.css';
import '../../css/e/eyjrvqbsq.css';
import '../../css/z/zs55ho22r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="xn4aaqbkb"/><path class="eyjrvqbsq"/><path class="zs55ho22r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:camera-reels-fill" {...props}></Icon>
