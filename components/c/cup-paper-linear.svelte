<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ir6vhdc8p.css';
import '../../css/c/c88w_27gk.css';
import '../../css/t/tk6t9fbyh.css';
import '../../css/j/jxdwkm1he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ir6vhdc8p"/><path class="c88w_27gk"/><path class="tk6t9fbyh"/><path class="jxdwkm1he"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cup-paper-linear" {...props}></Icon>
