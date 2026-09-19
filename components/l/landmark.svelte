<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nstqkuwkl.css';
import '../../css/v/vzlc76b1w.css';
import '../../css/j/j0lrf0bvw.css';
import '../../css/y/y5ojkzbkl.css';
import '../../css/c/c51t0pb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nstqkuwkl"/><path class="vzlc76b1w"/><path class="j0lrf0bvw"/><path clip-rule="evenodd" class="y5ojkzbkl"/><path class="c51t0pb6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:landmark" {...props}></Icon>
