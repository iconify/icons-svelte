<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fhikcfy3j.css';
import '../../css/e/emoy9fbht.css';
import '../../css/q/qso9u0yuv.css';
import '../../css/b/bci37w2ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fhikcfy3j"/><path class="emoy9fbht"/><path class="qso9u0yuv"/><path class="bci37w2ik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clipboard-copy-duotone" {...props}></Icon>
