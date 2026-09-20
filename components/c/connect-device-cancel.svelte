<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rfgqaxbee.css';
import '../../css/s/svxtvccuv.css';
import '../../css/k/k_pt_skzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rfgqaxbee"/><path class="svxtvccuv"/><path class="k_pt_skzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:connect-device-cancel" {...props}></Icon>
