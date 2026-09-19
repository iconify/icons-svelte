<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nlaso0bdo.css';
import '../../css/u/ub71xqbpj.css';
import '../../css/u/utr6ahyvf.css';
import '../../css/m/mm1d9kbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nlaso0bdo"/><path class="ub71xqbpj"/><path class="utr6ahyvf"/><path class="mm1d9kbpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-add-duo" {...props}></Icon>
