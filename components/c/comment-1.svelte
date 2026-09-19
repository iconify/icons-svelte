<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j0uu7sblb.css';
import '../../css/j/jx9zyu03l.css';
import '../../css/o/o4ej_lc-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="j0uu7sblb"/><path class="jx9zyu03l"/><circle class="o4ej_lc-u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:comment-1" {...props}></Icon>
