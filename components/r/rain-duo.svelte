<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/deia9eb9b.css';
import '../../css/p/p4hny8b2l.css';
import '../../css/b/bup-tl2ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="deia9eb9b"/><path class="p4hny8b2l"/><path class="bup-tl2ej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:rain-duo" {...props}></Icon>
