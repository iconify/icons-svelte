<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zifwembjz.css';
import '../../css/r/rbpght8ec.css';
import '../../css/t/t7ns7tbvi.css';
import '../../css/x/x6zc0oj6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zifwembjz"/><path class="rbpght8ec"/><path class="t7ns7tbvi"/><path class="x6zc0oj6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:handshake-duo" {...props}></Icon>
