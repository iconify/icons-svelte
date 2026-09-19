<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyji3vb3h.css';
import '../../css/b/b3dn0_1qr.css';
import '../../css/e/e1a212beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="nyji3vb3h"><path class="b3dn0_1qr"/><path class="e1a212beq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:canva" {...props}></Icon>
