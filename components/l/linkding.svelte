<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy8m0sbcq.css';
import '../../css/e/etynb-byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="zy8m0sbcq"/><path class="etynb-byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkding" {...props}></Icon>
