<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/urue2_g_v.css';
import '../../css/a/acuj0xb6z.css';
import '../../css/t/th2izabht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="urue2_g_v"/><path class="acuj0xb6z"/><path class="th2izabht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bezier-hexagon-duo" {...props}></Icon>
