<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o8k0k3bla.css';
import '../../css/w/wnley4fnf.css';
import '../../css/l/lu_0-xpbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="o8k0k3bla"/><path class="wnley4fnf"/><path clip-rule="evenodd" class="lu_0-xpbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:layer-backward" {...props}></Icon>
