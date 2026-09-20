<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/u/uokp1hb7l.css';
import '../../css/o/o8t6onbpn.css';
import '../../css/h/hkms2nksv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="uokp1hb7l"/><path class="o8t6onbpn"/></g><path class="hkms2nksv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cash-out-bold-duotone" {...props}></Icon>
