<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zqhz5k-uj.css';
import '../../css/n/njmfmmnsj.css';
import '../../css/a/a0-uj79up.css';
import '../../css/y/ye6al5vfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zqhz5k-uj"/><path clip-rule="evenodd" class="njmfmmnsj"/><path class="a0-uj79up"/><path clip-rule="evenodd" class="ye6al5vfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-pad-outline" {...props}></Icon>
