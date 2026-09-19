<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tr7sirbvc.css';
import '../../css/e/ej5a_l4in.css';
import '../../css/k/kgtb4abpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tr7sirbvc"/><path class="ej5a_l4in"/><path class="kgtb4abpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hat-glasses" {...props}></Icon>
