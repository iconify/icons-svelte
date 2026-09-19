<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i1cf-cbwa.css';
import '../../css/w/wflhrrs6l.css';
import '../../css/v/vfm78o92s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="i1cf-cbwa"/><path class="wflhrrs6l"/><path class="vfm78o92s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:barcode-scan-bold" {...props}></Icon>
