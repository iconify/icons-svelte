<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xq37n2byd.css';
import '../../css/v/vg2lsqbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xq37n2byd"/><path class="vg2lsqbky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:fire" {...props}></Icon>
