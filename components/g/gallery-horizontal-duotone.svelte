<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i03ibwbly.css';
import '../../css/n/n1sguyb9y.css';
import '../../css/l/l520w2onl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i03ibwbly"/><path class="n1sguyb9y"/><path class="l520w2onl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gallery-horizontal-duotone" {...props}></Icon>
