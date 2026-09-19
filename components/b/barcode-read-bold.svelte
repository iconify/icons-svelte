<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/s/s4cl7284p.css';
import '../../css/o/oln1prb6w.css';
import '../../css/u/ubdxevbux.css';
import '../../css/k/ko4f4urva.css';
import '../../css/n/ngb3iwz0p.css';
import '../../css/p/pe6sd5bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="pr52f_b5y"><path class="s4cl7284p"/><rect class="oln1prb6w"/><rect class="ubdxevbux"/><rect class="ko4f4urva"/><rect class="ngb3iwz0p"/><rect class="pe6sd5bcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:barcode-read-bold" {...props}></Icon>
