<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n4adrdbbc.css';
import '../../css/w/wpr94kbcg.css';
import '../../css/o/o278vf_zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="n4adrdbbc"/><path class="wpr94kbcg"/><path class="o278vf_zl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:mobile-1" {...props}></Icon>
