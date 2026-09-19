<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e5k9mhbdo.css';
import '../../css/o/ob8xw0bkr.css';
import '../../css/r/r3s12lbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="e5k9mhbdo"/><path class="ob8xw0bkr"/><path class="r3s12lbsu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:female" {...props}></Icon>
