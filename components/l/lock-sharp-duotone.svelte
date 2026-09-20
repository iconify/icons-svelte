<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/s/szxt87bjn.css';
import '../../css/q/qj8iipbgi.css';
import '../../css/d/d-2r4nbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="szxt87bjn"/><path class="qj8iipbgi"/><path clip-rule="evenodd" class="d-2r4nbvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:lock-sharp-duotone" {...props}></Icon>
