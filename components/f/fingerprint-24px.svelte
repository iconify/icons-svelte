<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d3urgtb2i.css';
import '../../css/b/bx8jjl-jo.css';
import '../../css/a/acyy7bb5r.css';
import '../../css/y/ym1ut9bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d3urgtb2i"/><path class="bx8jjl-jo"/><path class="acyy7bb5r"/><path class="ym1ut9bxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:fingerprint-24px" {...props}></Icon>
