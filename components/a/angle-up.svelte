<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ubgg72beu.css';
import '../../css/h/h6g2bb68s.css';
import '../../css/d/ds5qc2bnf.css';
import '../../css/w/w-xkhkb-i.css';
import '../../css/f/fpwcizi8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ubgg72beu"/><path class="h6g2bb68s"/><path class="ds5qc2bnf"/><path class="w-xkhkb-i"/><path class="fpwcizi8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:angle-up" {...props}></Icon>
