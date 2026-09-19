<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jy78hpq8b.css';
import '../../css/q/qujowbbuv.css';
import '../../css/i/itd8vpbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="jy78hpq8b"/><path class="qujowbbuv"/><path class="itd8vpbbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:leaf-1" {...props}></Icon>
