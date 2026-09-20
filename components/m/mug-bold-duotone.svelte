<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/c/cf4va2ows.css';
import '../../css/l/ldse3ccpn.css';
import '../../css/u/uryn3_6yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="cf4va2ows"/><path class="ldse3ccpn"/></g><path clip-rule="evenodd" class="uryn3_6yg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mug-bold-duotone" {...props}></Icon>
