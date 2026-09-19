<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/ophjqrt4l.css';
import '../../css/e/euedu3ulz.css';
import '../../css/q/q-hojtojq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ophjqrt4l"/><path class="euedu3ulz"/><path class="q-hojtojq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cellular-network" {...props}></Icon>
