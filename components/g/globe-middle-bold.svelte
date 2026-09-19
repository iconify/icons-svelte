<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bpin_ybto.css';
import '../../css/e/ecby_rb4p.css';
import '../../css/x/xor-uacie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bpin_ybto"/><path clip-rule="evenodd" class="ecby_rb4p"/><path class="xor-uacie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-middle-bold" {...props}></Icon>
