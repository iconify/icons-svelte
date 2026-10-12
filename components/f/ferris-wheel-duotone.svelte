<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nzmariesu.css';
import '../../css/n/nbqssjb9c.css';
import '../../css/b/bbpijxb0t.css';
import '../../css/s/smguzlbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nzmariesu"/><path class="nbqssjb9c"/><path class="bbpijxb0t"/><path class="smguzlbht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ferris-wheel-duotone" {...props}></Icon>
