<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgw988bsm.css';
import '../../css/g/gn5j3-b2t.css';
import '../../css/u/u11od-bgv.css';
import '../../css/f/fzy27luea.css';
import '../../css/e/ejk1ck6md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zgw988bsm"/><path class="gn5j3-b2t"/><path class="u11od-bgv"/><path class="fzy27luea"/><path class="ejk1ck6md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mini-qr" {...props}></Icon>
