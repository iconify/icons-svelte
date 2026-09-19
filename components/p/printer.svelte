<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rdcrbbapn.css';
import '../../css/d/d2kaccbjd.css';
import '../../css/g/g_1c4cz4t.css';
import '../../css/l/lnzxizbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="rdcrbbapn"/><path class="d2kaccbjd"/><rect class="g_1c4cz4t"/><path clip-rule="evenodd" class="lnzxizbxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:printer" {...props}></Icon>
