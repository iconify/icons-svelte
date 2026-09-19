<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kv-q7zb1z.css';
import '../../css/l/l_mxcqb6a.css';
import '../../css/q/qnkm3hpka.css';
import '../../css/a/a9a8a3b1z.css';
import '../../css/p/pdlzyf8aw.css';
import '../../css/h/hg8tqkb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="kv-q7zb1z"/><path class="l_mxcqb6a"/><path clip-rule="evenodd" class="qnkm3hpka"/><path clip-rule="evenodd" class="a9a8a3b1z"/><path class="pdlzyf8aw"/><path clip-rule="evenodd" class="hg8tqkb-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:barcode-outline" {...props}></Icon>
