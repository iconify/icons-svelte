<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rd3od2-zf.css';
import '../../css/e/evv8tz29n.css';
import '../../css/n/npphhda2s.css';
import '../../css/x/xw_ykbbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rd3od2-zf"/><path clip-rule="evenodd" class="evv8tz29n"/><path class="npphhda2s"/><path clip-rule="evenodd" class="xw_ykbbuu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:industry-outline" {...props}></Icon>
