<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mgsf0f4kg.css';
import '../../css/b/b60xnhcqr.css';
import '../../css/n/ncm95bc2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="mgsf0f4kg"/><path class="b60xnhcqr"/><path class="ncm95bc2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-squint-tears-duo" {...props}></Icon>
