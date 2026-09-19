<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l0odr6zsw.css';
import '../../css/d/dz_acn-zs.css';
import '../../css/f/f78tv89nt.css';
import '../../css/m/m4m9b5sui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><rect class="l0odr6zsw"/><path clip-rule="evenodd" class="dz_acn-zs"/><path clip-rule="evenodd" class="f78tv89nt"/><path class="m4m9b5sui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:calendar-print" {...props}></Icon>
