<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l1wclibsf.css';
import '../../css/a/a7cf72bwi.css';
import '../../css/u/ujauf4b7r.css';
import '../../css/q/q0ddhhb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="l1wclibsf"/><path clip-rule="evenodd" class="a7cf72bwi"/><path clip-rule="evenodd" class="ujauf4b7r"/><path class="q0ddhhb0m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:lock-closed-print" {...props}></Icon>
