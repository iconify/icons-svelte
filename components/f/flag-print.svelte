<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t12lt_bso.css';
import '../../css/o/opuctyblu.css';
import '../../css/o/omgkgqbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="t12lt_bso"/><path clip-rule="evenodd" class="opuctyblu"/><path clip-rule="evenodd" class="omgkgqbgl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:flag-print" {...props}></Icon>
