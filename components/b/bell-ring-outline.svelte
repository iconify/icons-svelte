<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k05pohbcd.css';
import '../../css/p/p-4rrx1id.css';
import '../../css/z/z96i0eb1f.css';
import '../../css/e/elozc-x8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="k05pohbcd"/><path class="p-4rrx1id"/><path clip-rule="evenodd" class="z96i0eb1f"/><path class="elozc-x8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-ring-outline" {...props}></Icon>
