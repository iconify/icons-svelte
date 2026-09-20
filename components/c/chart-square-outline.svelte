<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/ppgcg01jg.css';
import '../../css/j/j3-m1tbbc.css';
import '../../css/c/chqrttdmo.css';
import '../../css/u/u5bqo67kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ppgcg01jg"/><path class="j3-m1tbbc"/><path class="chqrttdmo"/><path clip-rule="evenodd" class="u5bqo67kp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chart-square-outline" {...props}></Icon>
