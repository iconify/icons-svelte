<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iusmblaqn.css';
import '../../css/t/tnf8gbb-i.css';
import '../../css/l/l8q853blz.css';
import '../../css/f/f6a2dhcys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iusmblaqn"/><path class="tnf8gbb-i"/><path class="l8q853blz"/><path class="f6a2dhcys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bill-line-duotone" {...props}></Icon>
