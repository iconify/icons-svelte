<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a__s2g6zp.css';
import '../../css/f/f4sd56baf.css';
import '../../css/b/bbhoyd3dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="a__s2g6zp"><path class="f4sd56baf"/><path class="bbhoyd3dh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-charge-bold" {...props}></Icon>
