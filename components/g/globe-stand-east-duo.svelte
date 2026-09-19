<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t5oh21qle.css';
import '../../css/f/fweop44zq.css';
import '../../css/z/ztf5h5box.css';
import '../../css/h/hxvb2zb6c.css';
import '../../css/q/qg-npbc4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="t5oh21qle"/><path class="fweop44zq"/><path class="ztf5h5box"/><path class="hxvb2zb6c"/><path class="qg-npbc4r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-stand-east-duo" {...props}></Icon>
