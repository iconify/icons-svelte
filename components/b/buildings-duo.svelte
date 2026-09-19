<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cypp3g9oc.css';
import '../../css/m/mlztb_4gl.css';
import '../../css/q/q9bs_0ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="cypp3g9oc"/><path class="mlztb_4gl"/><path class="q9bs_0ber"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:buildings-duo" {...props}></Icon>
