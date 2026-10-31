<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jhsaz8brf.css';
import '../../css/x/xha3m7bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":201};
const content = `<g class="ft5dv1b6b"><path class="jhsaz8brf"/><path class="xha3m7bla"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:id" {...props}></Icon>
