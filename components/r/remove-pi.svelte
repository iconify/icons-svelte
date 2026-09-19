<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v10bhlb1p.css';
import '../../css/f/f9o0vpbpo.css';
import '../../css/k/kmc74e6rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v10bhlb1p"/><path class="f9o0vpbpo"/><path class="kmc74e6rd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:remove-pi" {...props}></Icon>
