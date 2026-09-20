<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-c8a2bra.css';
import '../../css/z/zbfz6_e-q.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/y/y1j8wi2gc.css';
import '../../css/c/cz-zmg-cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="z-c8a2bra"/><path class="zbfz6_e-q"/><g class="ij2x_72vy"><path class="y1j8wi2gc"/><circle class="cz-zmg-cw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:basketball" {...props}></Icon>
