<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/ftfhj4b0c.css';
import '../../css/k/k8ta0qmcg.css';
import '../../css/f/fvyp7-ged.css';
import '../../css/s/sxclq_x3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ftfhj4b0c"/><path class="k8ta0qmcg"/><path class="fvyp7-ged"/><path class="sxclq_x3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:die-5-outline" {...props}></Icon>
