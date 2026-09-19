<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vlx_mbcyg.css';
import '../../css/b/bo5ct3btu.css';
import '../../css/g/gch2qubat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vlx_mbcyg"/><path class="bo5ct3btu"/><path class="gch2qubat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:credit-card-front-duo" {...props}></Icon>
