<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fgi1oabxo.css';
import '../../css/y/ygwddxzjt.css';
import '../../css/j/jscgw910q.css';
import '../../css/g/gv00i1u7i.css';
import '../../css/u/uo39__bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="fgi1oabxo"/><path class="ygwddxzjt"/><path class="jscgw910q"/><path class="gv00i1u7i"/><path class="uo39__bxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:contract" {...props}></Icon>
