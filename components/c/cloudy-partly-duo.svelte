<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jvw3jkjnb.css';
import '../../css/n/nnd8v_bmg.css';
import '../../css/g/gv-lolbnd.css';
import '../../css/r/ropa7ebap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="jvw3jkjnb"/><path class="nnd8v_bmg"/><path class="gv-lolbnd"/><path class="ropa7ebap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cloudy-partly-duo" {...props}></Icon>
