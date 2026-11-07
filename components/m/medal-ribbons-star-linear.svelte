<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pfjefkbxt.css';
import '../../css/i/i6nrt8nnu.css';
import '../../css/r/rtsf20bbs.css';
import '../../css/b/bc8a__bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pfjefkbxt"/><path class="i6nrt8nnu"/><path class="rtsf20bbs"/><path class="bc8a__bpd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbons-star-linear" {...props}></Icon>
