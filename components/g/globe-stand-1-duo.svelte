<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t5oh21qle.css';
import '../../css/f/fweop44zq.css';
import '../../css/d/dixd5tz-u.css';
import '../../css/p/pkn-7v7fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="t5oh21qle"/><path class="fweop44zq"/><path class="dixd5tz-u"/><path class="pkn-7v7fr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-stand-1-duo" {...props}></Icon>
