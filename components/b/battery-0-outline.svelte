<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rg96irb-q.css';
import '../../css/e/e4mub5bik.css';
import '../../css/a/a2kumftht.css';
import '../../css/g/g99usobyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rg96irb-q"/><path clip-rule="evenodd" class="e4mub5bik"/><path class="a2kumftht"/><path clip-rule="evenodd" class="g99usobyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-0-outline" {...props}></Icon>
