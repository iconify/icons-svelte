<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f3wxftbjs.css';
import '../../css/i/ipu91p9hu.css';
import '../../css/d/d-6krk_4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="f3wxftbjs"/><path clip-rule="evenodd" class="ipu91p9hu"/><path class="d-6krk_4l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:lightbulb-2" {...props}></Icon>
