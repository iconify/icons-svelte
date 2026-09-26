<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i22s-4u1h.css';
import '../../css/t/t1j-_8esg.css';
import '../../css/d/dplnzz0rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i22s-4u1h"/><path class="t1j-_8esg"/><path class="dplnzz0rj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-bottom-right-linear" {...props}></Icon>
