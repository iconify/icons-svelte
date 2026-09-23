<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/vk9v_xb8o.css';
import '../../css/s/snibgdcaa.css';
import '../../css/n/n19x7nf9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vk9v_xb8o"/><path class="snibgdcaa"/><path class="n19x7nf9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:phone-sparkles-sharp-two-tone" {...props}></Icon>
