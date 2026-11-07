<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mbfzuei-h.css';
import '../../css/t/tnf8gbb-i.css';
import '../../css/z/zvakluojt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mbfzuei-h"/><path class="tnf8gbb-i"/><path class="zvakluojt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bill-cross-line-duotone" {...props}></Icon>
