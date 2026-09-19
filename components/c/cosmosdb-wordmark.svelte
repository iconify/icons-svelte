<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmkx4x2wi.css';
import '../../css/k/k79nfqmnv.css';
import '../../css/f/flaemkb3e.css';
import '../../css/h/h2gx32brp.css';
import '../../css/j/jbf8k0x2t.css';
import '../../css/b/bvxxlhroq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fmkx4x2wi"/><path class="k79nfqmnv"/><path class="flaemkb3e"/><path class="h2gx32brp"/><path class="jbf8k0x2t"/><path class="bvxxlhroq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:cosmosdb-wordmark" {...props}></Icon>
