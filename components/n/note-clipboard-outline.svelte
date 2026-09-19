<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zqhz5k-uj.css';
import '../../css/i/ivehi5u4g.css';
import '../../css/a/a0-uj79up.css';
import '../../css/q/qhecqmane.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zqhz5k-uj"/><path clip-rule="evenodd" class="ivehi5u4g"/><path class="a0-uj79up"/><path clip-rule="evenodd" class="qhecqmane"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-clipboard-outline" {...props}></Icon>
