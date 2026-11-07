<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oos2x6mvr.css';
import '../../css/r/rumgkrbdt.css';
import '../../css/j/joig5dakl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oos2x6mvr"/><path class="rumgkrbdt"/><path class="joig5dakl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dialog-broken" {...props}></Icon>
