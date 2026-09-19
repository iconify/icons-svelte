<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eum8pabgr.css';
import '../../css/t/tuua3db3n.css';
import '../../css/g/gng0j2b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="eum8pabgr"/><path class="tuua3db3n"/><path class="gng0j2b3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:baseball-1-duo" {...props}></Icon>
