<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r4l7ckptj.css';
import '../../css/m/mg6_t5b9m.css';
import '../../css/v/vv-z5phem.css';
import '../../css/k/k8owyt_1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="r4l7ckptj"/><path class="mg6_t5b9m"/><path class="vv-z5phem"/><path class="k8owyt_1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:repeat-bold" {...props}></Icon>
