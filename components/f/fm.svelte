<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pe9qg0rhv.css';
import '../../css/v/v4282eljr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":159};
const content = `<g class="ft5dv1b6b"><path class="pe9qg0rhv"/><path class="v4282eljr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:fm" {...props}></Icon>
