<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/epnj5wb4n.css';
import '../../css/i/ix_3swbon.css';
import '../../css/c/cxw_bfcfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="epnj5wb4n"/><path class="ix_3swbon"/><path class="cxw_bfcfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bitcoin-presentation" {...props}></Icon>
