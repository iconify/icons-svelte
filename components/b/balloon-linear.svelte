<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ixys9inif.css';
import '../../css/d/d0k502nsw.css';
import '../../css/e/efb3h0bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ixys9inif"/><path class="d0k502nsw"/><path class="efb3h0bra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:balloon-linear" {...props}></Icon>
