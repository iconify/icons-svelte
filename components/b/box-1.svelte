<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mu2a2galn.css';
import '../../css/n/n_o6seuop.css';
import '../../css/v/v35nnjbuw.css';
import '../../css/a/anjlg6eec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="mu2a2galn"/><path class="n_o6seuop"/><path class="v35nnjbuw"/><path class="anjlg6eec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:box-1" {...props}></Icon>
