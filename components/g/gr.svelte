<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fa6lstzyt.css';
import '../../css/p/pe-28bbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":201};
const content = `<g class="bi12bsetm"><path class="fa6lstzyt"/><path class="pe-28bbuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:gr" {...props}></Icon>
