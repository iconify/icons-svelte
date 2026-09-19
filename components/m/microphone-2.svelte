<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/otobglbfo.css';
import '../../css/w/whfc_wblo.css';
import '../../css/a/amcfhfbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="otobglbfo"/><path class="whfc_wblo"/><path clip-rule="evenodd" class="amcfhfbkw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:microphone-2" {...props}></Icon>
