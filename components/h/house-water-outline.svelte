<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/ceaub_u1f.css';
import '../../css/l/l9lejiboz.css';
import '../../css/d/dpbi1eb5g.css';
import '../../css/h/hwy146b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ceaub_u1f"/><path class="l9lejiboz"/><path class="dpbi1eb5g"/><path class="hwy146b6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:house-water-outline" {...props}></Icon>
