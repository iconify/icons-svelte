<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fa6pz-bnf.css';
import '../../css/n/ns5oz0btl.css';
import '../../css/p/pc9u2x3ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fa6pz-bnf"/><path class="ns5oz0btl"/><path class="pc9u2x3ft"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:binoculars-duotone" {...props}></Icon>
