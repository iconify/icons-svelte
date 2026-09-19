<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qmdl50mwg.css';
import '../../css/f/fr5kl9bxl.css';
import '../../css/z/zz1e7_bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="qmdl50mwg"/><path clip-rule="evenodd" class="fr5kl9bxl"/><path class="zz1e7_bjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:eye-print" {...props}></Icon>
