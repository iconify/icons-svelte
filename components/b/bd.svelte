<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f9e-ti8lb.css';
import '../../css/l/lr8d33b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":181};
const content = `<g class="ft5dv1b6b"><path class="f9e-ti8lb"/><circle class="lr8d33b7p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:bd" {...props}></Icon>
