<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vn9m1j_jt.css';
import '../../css/q/qg2qrmbrg.css';
import '../../css/n/np3qu_b3h.css';
import '../../css/v/v-hllac-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vn9m1j_jt"/><path class="qg2qrmbrg"/><path class="np3qu_b3h"/><path class="v-hllac-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-stars-bold" {...props}></Icon>
