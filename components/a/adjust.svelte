<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h7rof_xzg.css';
import '../../css/r/ry4xkfx6l.css';
import '../../css/i/ijc812t3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="h7rof_xzg"/><path clip-rule="evenodd" class="ry4xkfx6l"/><path clip-rule="evenodd" class="ijc812t3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:adjust" {...props}></Icon>
