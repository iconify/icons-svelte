<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4--ovbba.css';
import '../../css/u/uydycvbfl.css';
import '../../css/c/ci_ovbccc.css';
import '../../css/d/d47ryccpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l4--ovbba"/><path class="uydycvbfl"/><path class="ci_ovbccc"/><path class="d47ryccpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-pound" {...props}></Icon>
