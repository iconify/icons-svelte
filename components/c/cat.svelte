<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/t/tvg65tvki.css';
import '../../css/i/iagdctb2d.css';
import '../../css/e/eiys41bih.css';
import '../../css/p/pi6-q1i4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="tvg65tvki wm-shadow"/><path class="iagdctb2d wm-shadow"/><path class="eiys41bih"/><path class="pi6-q1i4h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:cat" {...props}></Icon>
