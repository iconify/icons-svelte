<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mk_pnxbej.css';
import '../../css/n/nhmln6bau.css';
import '../../css/x/xofm-lbrq.css';
import '../../css/l/lj2ryhrph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mk_pnxbej"/><path class="nhmln6bau"/><path class="xofm-lbrq"/><path class="lj2ryhrph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:farm-outline" {...props}></Icon>
