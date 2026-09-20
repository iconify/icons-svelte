<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d6yf8nbqe.css';
import '../../css/h/hfjwbrilq.css';
import '../../css/p/pxi4ntbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d6yf8nbqe"/><path class="hfjwbrilq"/><rect transform="rotate(44.97 12.113 1)" class="pxi4ntbrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:corkscrew-linear" {...props}></Icon>
