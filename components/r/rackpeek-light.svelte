<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lws_a6b-r.css';
import '../../css/u/ufdzejvac.css';
import '../../css/x/xsd8r2b6z.css';
import '../../css/c/cy-xakbxe.css';
import '../../css/z/zgsa_6y0q.css';
import '../../css/s/sqimm-owa.css';
import '../../css/d/dhi-t2w2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lws_a6b-r"/><path class="ufdzejvac"/><path class="xsd8r2b6z"/><path class="cy-xakbxe"/><path class="zgsa_6y0q"/><path class="sqimm-owa"/><path class="dhi-t2w2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rackpeek-light" {...props}></Icon>
