<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cerywbcfw.css';
import '../../css/n/nm5ghwbht.css';
import '../../css/h/hax6ymbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="cerywbcfw"/><path class="nm5ghwbht"/><path class="hax6ymbgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:map-marker-1" {...props}></Icon>
