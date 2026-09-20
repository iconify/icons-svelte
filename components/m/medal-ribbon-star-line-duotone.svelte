<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p-qrmibls.css';
import '../../css/i/i6nrt8nnu.css';
import '../../css/e/ey97octmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p-qrmibls"/><path class="i6nrt8nnu"/><path class="ey97octmt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbon-star-line-duotone" {...props}></Icon>
