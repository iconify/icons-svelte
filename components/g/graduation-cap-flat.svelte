<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vgoaambvi.css';
import '../../css/k/k0_cajbag.css';
import '../../css/l/ltk06_b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vgoaambvi"/><path class="k0_cajbag"/><path class="ltk06_b4f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:graduation-cap-flat" {...props}></Icon>
