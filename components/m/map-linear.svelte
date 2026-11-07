<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lg4hmt8ek.css';
import '../../css/t/t266g0bnv.css';
import '../../css/m/mszfd9biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lg4hmt8ek"/><path class="t266g0bnv"/><path class="mszfd9biq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-linear" {...props}></Icon>
