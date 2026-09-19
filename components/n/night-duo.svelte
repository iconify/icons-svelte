<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/krd41pbpp.css';
import '../../css/u/u2lu0e3iz.css';
import '../../css/w/ws4qkkash.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="krd41pbpp"/><path class="u2lu0e3iz"/><path class="ws4qkkash"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:night-duo" {...props}></Icon>
