<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kba12nbbt.css';
import '../../css/p/p3aehbcct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":130,"height":40};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGlvgrFbyM)" class="cuyn6tgcc"><path class="kba12nbbt"/></g><defs><clipPath id="SVGlvgrFbyM"><path class="p3aehbcct"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:minnesota-wild" {...props}></Icon>
