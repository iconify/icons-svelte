<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/r247vsbdl.css';
import '../../css/n/nkncs4b1r.css';
import '../../css/n/na9l3_b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r247vsbdl"/><path class="nkncs4b1r"/><path class="na9l3_b7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-opened-broken" {...props}></Icon>
