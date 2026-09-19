<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uz-biobdg.css';
import '../../css/g/gugmgrnjp.css';
import '../../css/d/d09h2ubln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="uz-biobdg"/><path class="gugmgrnjp"/><path clip-rule="evenodd" class="d09h2ubln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:car" {...props}></Icon>
